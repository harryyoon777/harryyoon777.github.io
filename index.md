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
I am a MS in Computer Science student at University of Maryland, College Park (Fall 24). Prior to that, I earned my Bachelor's degree from Kyung Hee University, where I worked with <a href="http://cvlab.khu.ac.kr/">Prof.Seungkyu Lee</a> in PerCV Lab.
<br/>
<br/>
<b>Research interest</b>
<br/>
Computer Graphics: Differentiable Rendering and Simulation


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
    <td style="text-align:left;vertical-align:top;padding-top:1%;padding-left:1%;" width="25%">    <img src="/images/publications/NeRF_for_transparent.jpg" align="left" width="250" style="cursor:pointer" onclick="window.open(this.src)"/>    </td>
    <td width="70%">    <a href="https://arxiv.org/abs/2312.08118"> 
      <strong>Neural Radiance Fields for Transparent Object Using Visual Hull</strong> </a> <br/> 
      <strong>Heechan Yoon</strong>, Seungkyu Lee<br/>
      <span style="color: green">IEEE BigComp 2024 </span> <strong></strong><br/>
      <a class="links" href="https://arxiv.org/abs/2312.08118"> Paper </a>
      <br>
      Neural Radiance Fields (NeRF) uses only straight rays. This leads to a challenge in representing scenes containing transparent object where refractions occur. To handle this problem, I proposed a method correct ray that refracts as it passes through a transparent object using Snell’s law.
    </td> 
  </tr>
</table>


<table style="background-color:#F1F7FC">
  <tr>
    <td style="text-align:left;vertical-align:top;padding-top:1%;padding-left:1%;" width="25%">    <img src="/images/publications/reflection_remove.png" align="left" width="250" style="cursor:pointer" onclick="window.open(this.src)"/>    </td>
    <td width="70%">    <a href="https://arxiv.org/abs/2312.03798"> 
      <strong>Single Image Reflection Removal with Reflection Intensity Prior Knowledge</strong> </a> <br/> 
      Dongshen Han, Seungkyu Lee, Chaoning Zhang, <strong>Heechan Yoon</strong>, Hyukmin Kwon, HyunCheol Kim, HyonGon Choo<br/>
      <a class="links" href="https://arxiv.org/abs/2312.03798"> Paper </a>
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
     The movement of the hand is tracked using the RGB camera so that the puppet can move according to the movement of the finger. In addition, it recognizes specific hand gestures so that a predetermined action can be taken. <br>
     Left hand: thumb and midlle finger - puppet's arms, index finger - upper body <br>
     Right hand: peace gesture - run <br>
    </td> 
  </tr>
</table>


<hr/>
<font size="4">
<div align="left"><b>Projects</b></div> <br/>
</font>

<table style="background-color:#F1F7FC">
  <tr>
    <td style="text-align:left;vertical-align:top;padding-top:1%;padding-left:1%;" width="25%">    <img src="/images/projects/3D_Recon.png" align="left" width="500" style="cursor:pointer" onclick="window.open(this.src)"/>    </td>
    <td width="70%">
    <strong>3D reconstruction</strong><br>
  Project called 'Improving Texture Quality Using Material Properties' organized by ETRI(Electronics and Telecommunications Research Institute), South Korea. <br>
  <br>
  3D reconstruction with texture mapping.<br>
    </td> 
  </tr>
</table>

<table style="background-color:#F1F7FC">
<tr>
    <td style="text-align:left;vertical-align:top;padding-top:1%;padding-left:1%;" width="50%">    <img src="/images/projects/roughness.jpg" align="left" width="500" style="cursor:pointer" onclick="window.open(this.src)"/>    </td>
    <td width="70%">
    <strong>Roughness map </strong><br>
  I assigned roughness value to individual faces and made roughness map. Our model(The bottom of the image) more realistically portrays light interactions corresponding to the material as the light source moves (left --> right). 
 <br>
    </td> 
  </tr>
</table>

<table style="background-color:#F1F7FC">
<tr>
    <td style="text-align:left;vertical-align:top;padding-top:1%;padding-left:1%;" width="50%">    <img src="/images/projects/weight.png" align="left" width="500" style="cursor:pointer" onclick="window.open(this.src)"/>    </td>
    <td width="70%">
    <strong> Weight calculation of angle and distance difference </strong><br>
  By computing the angle between the camera direction and the mapping face normal vector, as well as the distance to the mapped face, I assigned more weight to images captured from the front and closer distances of the face.
<br>
    </td> 
  </tr>
</table>

<table style="background-color:#F1F7FC">
<tr>
    <td style="text-align:left;vertical-align:top;padding-top:1%;padding-left:1%;" width="50%">    <img src="/images/projects/atlas.png" align="left" width="500" style="cursor:pointer" onclick="window.open(this.src)"/>    </td>
    <td width="70%">
    <strong>Reduced the data size of texture atlas </strong><br>
  The binary image represents the face groups in white and the absent areas in black. To minimize the wasted black space between face groups, I found empty rectangles among n-vertex general polygons and insert textures into these spaces.
<br>
    </td> 
  </tr>
</table>


<br>
