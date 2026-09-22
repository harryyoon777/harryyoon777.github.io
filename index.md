---
layout: home
author_profile: true
classes: wide
---
<style>
a.paper:link, a.paper:visited {
  background-color: #E95D16;
  color: white;
  padding: 5px 5px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
}

a.paper:hover, a.paper:active {
  background-color: red;
}
a.links:link, a.links:visited {
  background-color: none;
  color: blue;
  border-style: solid;
  border-width: thin;
  border-color: blue;
  padding: 3px 3px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
}

a.links:hover, a.links:active {
  background-color: blue;
  color: white;
  border-style: solid;
  border-color: black;
}

a.genlinks:link, a.genlinks:visited {
  background-color: none;
  color: #66B2FF;
  display: inline-block;
}

/*Block Quote CSS Styles below*/
@import url(https://fonts.googleapis.com/css?family=EB+Garamond|Droid+Serif|Playfair+Display|Open+Sans+Condensed:300);

*, *:after, *:before {
    -webkit-box-sizing: border-box;
       -moz-box-sizing: border-box;
            box-sizing: border-box;
}

p {
    line-height: 1.4em;
}

.quote {
    position: relative;
    letter-spacing: .03em;
    margin-bottom: .5rem;
    
    &:before {
        content: "“";
        position: absolute;
        left: -.7em;
    }
    
    &:after {
        content: "”";
        margin-right: -1rem;
    }
}

.quote--container {
    margin: 3.5rem auto 0;
    width: 55%;
    /*border-bottom: 2px dotted #C6D1BF;*/
    padding-bottom: .5rem;
}

.quote--highlight {
    color: #D24335;
}

.quote--author {
    font-family: 'Open Sans Condensed';
    font-size: .8rem;
    text-align: right;
    font-weight: 300;
}


</style>

Hi! I am Heechan Yoon.
<br/>
I am a MS in Computer Science student at University of Maryland, College Park. Prior to that, I earned my Bachelor's degree from Kyung Hee University, where I worked with <a href="http://cvlab.khu.ac.kr/">Prof.Seungkyu Lee</a> in PerCV Lab.
<br/>
<br/>
<b>Research interest</b>
<br/>
Computer Vision and Robotics


<!-- <hr/>
<font size="4">
<div align="center"><b>News</b></div>
</font>

**08/22:** abcd</a>. <br/>

<hr/> -->

<font size="4">
<div align="left"><b>Publications</b></div> <br/>
</font>

<table style="background-color:#F1F7FC">
  <tr>
    <td style="text-align:left;vertical-align:top;padding-top:1%;padding-left:1%;" width="25%">    <img src="/images/publications/panoseg3r_teaser.png" align="left" width="250" style="cursor:pointer" onclick="window.open(this.src)"/>    </td>
    <td width="70%">
      <strong>PanoSeg3R: Feed-Forward 3D Semantic Segmentation for Panoramic Images with an Automatic Data Curation Pipeline</strong> <br/> 
      <strong>Heechan Yoon</strong>, Dongki Jung, Phuc Nguyen, Ming Lin, Dinesh Manocha<br/>
      <a href="/PanoSeg3R/">[Project]</a>
      <a href="https://arxiv.org/pdf/2609.22687">[arxiv]</a>
      <br>
      We present PanoSeg3R, a feed-forward framework for 3D panoramic semantic segmentation.
    </td> 
  </tr>
</table>


<table style="background-color:#F1F7FC">
  <tr>
    <td style="text-align:left;vertical-align:top;padding-top:1%;padding-left:1%;" width="25%">    <img src="/images/publications/NeRF_for_transparent.jpg" align="left" width="250" style="cursor:pointer" onclick="window.open(this.src)"/>    </td>
    <td width="70%">
      <strong>Neural Radiance Fields for Transparent Object Using Visual Hull</strong> <br/> 
      <strong>Heechan Yoon</strong>, Seungkyu Lee<br/>
      <span style="color: green">IEEE BigComp 2024 </span> <strong></strong><br/>
      <a href="https://arxiv.org/abs/2312.08118">[arXiv]</a>
      <br>
      We model refraction through transparent objects by correcting NeRF rays using Snell’s law.
    </td> 
  </tr>
</table>


<table style="background-color:#F1F7FC">
  <tr>
    <td style="text-align:left;vertical-align:top;padding-top:1%;padding-left:1%;" width="25%">    <img src="/images/publications/reflection_remove.png" align="left" width="250" style="cursor:pointer" onclick="window.open(this.src)"/>    </td>
    <td width="70%">
      <strong>Single Image Reflection Removal with Reflection Intensity Prior Knowledge</strong> <br/> 
      Dongshen Han, Seungkyu Lee, Chaoning Zhang, <strong>Heechan Yoon</strong>, Hyukmin Kwon, HyunCheol Kim, HyonGon Choo<br/>
      <a href="https://arxiv.org/abs/2312.03798">[arXiv]</a>
      <br>
      Single image reflection removal.

    </td> 
  </tr>
</table>

<table style="background-color:#F1F7FC">
  <tr>
    <td style="text-align:left;vertical-align:top;padding-top:1%;padding-left:1%;" width="25%">    <img src="/images/publications/transparent_segment.jpg" align="left" width="250" style="cursor:pointer" onclick="window.open(this.src)"/>    </td>
    <td width="70%">
      <strong>Internal-External Boundary Attention Fusion for Glass Surface Segmentation</strong> <br/> 
      Dongshen Han, Seungkyu Lee, <strong>Heechan Yoon</strong>, Hyukmin Kwon, Hyun-Cheol Kim, Hyon-Gon Choo<br/>
      <br>
      Detecting glass regions from a single-color image
    </td> 
  </tr>
</table>

<table style="background-color:#F1F7FC">
  <tr>
    <td style="text-align:left;vertical-align:top;padding-top:1%;padding-left:1%;" width="25%">    <img src="/images/publications/capstone.gif" align="left" width="250" style="cursor:pointer" onclick="window.open(this.src)"/>    </td>
    <td width="70%">
    <strong>Virtual Puppet Control using 2D video Hand Tracking and Facial Emotion Recognition</strong> <br/> 
     Jueun Mun*, Gangyeon Go*, <strong>Heechan Yoon*</strong>, Yewon Han*, Seungkyu Lee.<br>
     <br>
     Puppet control using finger movements and hand gestures.
    </td> 
  </tr>
</table>



<br>
