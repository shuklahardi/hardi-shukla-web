---
layout: home
---
<button onclick="topFunction()" id="totop" title="Go to top">↑</button>

<!-- Photo Grid -->
<div class="row"> 
  <div class="column">
    <img src="/assets/images/1.webp" style="width:100%" class="image"> 
    <p class="phome">Champak Magazine | Story: The Mighty Mouse</p>
    <img src="/assets/images/Bee1.webp" style="width:100%">
    <p class="phome">Bee Illustration</p>
    <img src="/assets/images/5.webp" style="width:100%">
    <p class="phome">Champak Magazine | Story: Holi Bet</p>
      <img src="/assets/images/tiger.webp" style="width:100%">
      <p class="phome">llustrating the spirit of the wild</p>
    <img src="/assets/images/3.webp" style="width:100%">
     <p class="phome">Champak Magazine | Story: Shera Breaks a Bad Habit</p>
      <img src="/assets/images/turtle.webp" style="width:100%">
      <p class="phome">A slow and steady adventure</p>
      <img src="/assets/images/g.webp" style="width:100%">
      <p class="phome">Champak Magazine | Story: Tarun's Tale</p>
  </div>
  <div class="column">
    <img src="/assets/images/2.webp" style="width:100%">
    <p class="phome">Champak Magazine | Story: The Invisible Power</p>
    <img src="/assets/images/girraffe.webp" style="width:100%">
    <p class="phome">A Tall Tale</p>
     <img src="/assets/images/4.webp" style="width:100%">
      <p class="phome">Champak Magazine | Story: The Mighty Mouse</p>
     <img src="/assets/images/6.webp" style="width:100%">
     <p class="phome">Champak Magazine | Story: The Invisible Power</p>
     <img src="/assets/images/neurongirl.webp" style="width:100%">
     <p class="phome">Where imagination meets science</p>
     <img src="/assets/images/amibaa.webp" style="width:100%">
     <p class="phome">Exploring the magic of science</p>
     <img src="/assets/images/4-pro.webp" style="width:100%">
      <p class="phome">Champak Magazine | Story: A Fair Chance</p>
     </div>  
   </div>

   <script>
// Get the button
let totop = document.getElementById("totop");

// When the user scrolls down 20px from the top of the document, show the button
window.onscroll = function() {scrollFunction()};

function scrollFunction() {
  if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
    totop.style.display = "block";
  } else {
    totop.style.display = "none";
  }
}

// When the user clicks on the button, scroll to the top of the document
function topFunction() {
  document.body.scrollTop = 0;
  document.documentElement.scrollTop = 0;
}
</script>
