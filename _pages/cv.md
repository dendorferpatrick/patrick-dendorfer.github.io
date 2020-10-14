---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<style type="text/css">
    
    table {
        border: none;
        table-layout: fixed; 
          width: 100%;

        }

    img {
        width: 70%;
          }
      
  td img{
      display: block;
      margin-left: auto;
      margin-right: auto;

  }
   
    
    p.title {
        margin:0;
        font-size: 16px;
        text-align: justify;
        valign:"top";
        font-weight: bold;
       
    }
    
    p.dates {
        color: #7A8288;
        font-size: 14px;
        text-align: justify;
        valign:"top";
       
    }
    
   p.items {
         margin:0;
       font-size: 14px;
       text-align: justify;
       valign:"top";

    }
    
    p.position {
     
    
    }
   
    ul {    margin-block-start: 0.2em;
            margin-block-end: 0em;
            }
                                    

    td { text-align: left;
        vertical-align: top;
        border: none;
        margin-bottom: 500px 

      }
      
      #rcorners1 {
        border-radius: 25px;
       
        padding-left: 20px; 
        padding-right: 20px; 
        padding-top: 5px; 
        padding-bottom: 5px; 
  
      }
    


}
</style>
{% include base_path %}

<h2>Education</h2>


<div> 
<table>
{% assign education_ordered = site.education | sort: 'date' | reverse %}
{% for post in education_ordered %}
<tr>
<td > 
<img src="{{post.image_url}}">
</td>
<td colspan="4"> 
<p class="title">{{post.title}}</p>
<p class="position">{{post.description}}</p>
{% if post.items %}
<ul>
{% for item in post.items %}
 <li><p class="items">{{item}}</p></li>
{% endfor %}
</ul>
{% endif %}
</td>
<td><p class="dates">{{post.duration}}</p></td>

</tr>
  {% endfor %}
</table>
</div>



<h2>Working Experience</h2>

<div> 
<table>
{% assign work_ordered = site.work | sort: 'date' | reverse %}
 {% for post in work_ordered %}
<tr>
<td > 
<img src="{{post.image_url}}">
</td>
<td colspan="4"> 
<p class="title">{{post.title}}</p>
<p class="position">{{post.description}}</p>
{% if post.items %}
<ul>
{% for item in post.items %}
 <li><p class="items">{{item}}</p></li>
{% endfor %}
</ul>
{% endif %}

</td>
<td><p class="dates">{{post.duration}}</p></td>

</tr>
  {% endfor %}
</table>
</div>


<h2>Skills</h2>
<div>
<table>
{% for post in site.skills %}
<tr>
<td><p class="title">{{post.title}}:</p></td>
<td colspan="5">
{% for item in post.items %}
<span id="rcorners1"  style="background:{{post.color}}">
{{item}}  
</span>
{% endfor %}
</td>
</tr>
  {% endfor %}

</table>
</div>


<h2>Conference Workshops</h2>
<div>
<table>
{% for post in site.workshops reversed %}

  {% include archive-single-workshop.html %}
{% endfor %}
</table>
</div>



<h2>Teaching</h2>
<div>
<table>
{% for post in site.teaching reversed %}
  {% include archive-single-teaching.html %}
{% endfor %}
</table>
</div>
