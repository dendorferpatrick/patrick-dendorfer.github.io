---
title: "Pedestrian Trajectory Prediction"
collection: research
permalink: 
excerpt: 
date: 2019-06-1
venue: 'arXiv:1906.04567'
paperurl: 'https://arxiv.org/pdf/1906.04567.pdf'
thumbnail: "https://www.treehugger.com/thmb/rUWIJot2DDiFSlRqKk1LkWbgf5Q=/2048x1152/smart/filters:no_upscale()/__opt__aboutcom__coeus__resources__content_migration__mnn__images__2016__10__cloud-ground-lightning-f71bba67383949648b1e519588c26342.jpg" 
---
<p class="text">Pedestrian Trajectory Prediction is the task of predicting a set of possible future trajectories for a given observation. This ability is 
indispensable for any autonomous platform navigating through crowded scenes and interacting with humans.
In recent years, many research papers have leveraged the power of gernative models in order to predict a set of possible future trajectories.</p>
<p class="text">In my research I particulary study multimodality of trajectory predictions. In particualr, I am interested in building models that predict a set of divers but still realistic trajectories.</p>
<h3>Goal-GAN</h3>
<p class="text">In our ACCV 20 oral paper  <a href="https://arxiv.org/pdf/2010.01114.pdf">"<em>Goal-GAN: Multimodal Trajectory Prediction Based on Goal Position Estimation</em>"</a> we build a model that learns a discrete probaility 
map of future intermediate goal positions. These goal positions are used to pre-condition the 
decoder to generate the final trajectory.</p>
<div> 
<table>
<tr>
<td>
<img src="{{base_url}}/images/research/TrajPed/gif_0.gif" />
</td>
<td>
<img  src="{{base_url}}/images/research/TrajPed/gif_2.gif" />
</td>
<td>
<img src="{{base_url}}/images/research/TrajPed/gif_3.gif" />
</td>
</tr>
</table>
</div>
<p class="text">For more information about Goal-GAN check out the links below:</p>
<table class="TabResearch">
<tr>
<td><p class="text" style="text-align: center"><span class="fa fa-fw fa-file-pdf-o"></span><a target="_blank" href="https://arxiv.org/pdf/2010.01114.pdf">[pdf]</a></p></td>
<td><p class="text" style="text-align: center"><span class="fa fa-fw fa-code"></span><a target="_blank" href="https://github.com/dendorferpatrick/GoalGAN">[code]</a></p></td>
<td><p class="text" style="text-align: center"><span class="fa fa-fw fa-video-camera"></span><a target="_blank" href="https://youtu.be/SoMbBNpAQOw">[video]</a></p></td>
<td><p class="text" style="text-align: center"><span class="fa fa-globe"></span><a target="_blank" href="https://dendorferpatrick.github.io/GoalGAN/">[Project Page]</a></p></td>
</tr>
</table>
<h3>Student Projects</h3>
<p class="text">Next to my main research I constantly supervise students for a guided research project or their theses, especially in the field of pedestrian trajectory prediction. If you are a student from TU Munich and motivated in doing a research project in Pedin that field please contact me via
 <a href="mailto:patrick.dendorfer@tum.de">mail</a>.</p> 
<ul>
<li><p class="text">Philipp Mondorff: <a href="https://github.com/PMMon/Thesis_Social_Interactions">Modeling Social Interactions for Pedestrian Trajectory Prediction on Real and Synthetic Datasets</a></p></li>
<li><p class="text">David Glavas:  <a href="https://github.com/davidglavas/sgan-experiments">Studying Social Interactions in S-GAN</a></p></li>
</ul>