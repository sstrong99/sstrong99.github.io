---
layout: s-custom-css
title: Custom CSS
date: 2019-11-12 11:19:06.000000000 -07:00
type: s-custom-css
parent_id: '0'
published: true
password: ''
status: publish
categories: []
tags: []
meta:
  wordpress_post: '7'
author:
  login: strong1
  email: strong1@uchicago.edu
  display_name: strong1
  first_name: Steven
  last_name: Strong
permalink: "/strong1/s-custom-css/custom-css/"
excerpt: custom-css-1574456030.min.css
---
#site-title {font-size: 3.5rem;}  
#site-description {font-size: 1.5rem;}  
a:hover, .entry-title a:hover {text-decoration: underline;}

/\* this stops images from floating on mobile screen \*/  
@media only screen and (max-width: 500px) {  
 div.box {  
 display: inline  
 }  
 figure.alignleft, img.alignleft, figure.alignright, img.alignright {  
 float:none;  
 }  
}

.box { /\* this aligns figs and text vertically \*/  
 display: flex;  
 align-items: start;  
}

.alignleft {  
 float: left;  
 margin-right: 1.5em;  
 margin-bottom: 1.5em;  
}

.text {  
 margin-bottom: 1.0em;  
 overflow: hidden; /\* this is what keep the from wrapping \*/  
 text-align:justify  
}

