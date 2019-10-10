---
permalink: /
title: "Welcome to the Lifespan Decision-Making Lab!"
excerpt: "Home"
author: "LDM Lab"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<img class="mySlides" src="images/placeholder_group.jpeg">
<img class="mySlides" src="images/placeholder_group.jpeg">
<img class="mySlides" src="images/placeholder_group.jpeg">
<img class="mySlides" src="images/placeholder_group.jpeg">

<button class="w3-button w3-display-left" onclick="plusDivs(-1)">&#10094;</button>
<button class="w3-button w3-display-right" onclick="plusDivs(+1)">&#10095;</button>
var slideIndex = 1;
showDivs(slideIndex);

function plusDivs(n) {
  showDivs(slideIndex += n);
}

function showDivs(n) {
  var i;
  var x = document.getElementsByClassName("mySlides");
  if (n > x.length) {slideIndex = 1}
  if (n < 1) {slideIndex = x.length} ;
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";
  }
  x[slideIndex-1].style.display = "block";
}
<br><br>

How do children and young adult differ in how they learn? How does this learning change in old age? What factors contribute to optimal decision-making strategies? 

The primary goal of our research is to gain a better understanding of the cognitive and neural mechanisms underlying changes in learning and decision-making across the human lifespan. The LDM lab, directed by Dr. Ben Eppinger, studies how age affects learning mechanisms and decision-making strategies. 


Some of our research questions include:
======
A) What are the neuro-computational mechanisms underlying learning in uncertain environments and how do these learning processes develop across the human lifespan?

B) How does the ability to select and arbitrate between different learning strategies change as a function of age? 

C) How do humans learn from the behavior of other individuals and how does this ability change during lifespan development? 
