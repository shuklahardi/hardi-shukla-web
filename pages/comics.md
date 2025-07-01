---
layout: home
---
<button onclick="topFunction()" id="totop" title="Go to top">↑</button>

<!-- Photo Grid -->
<div class="comicrow"> 
  <div class="comiccolumn">
    <img src="/assets/images/comics/refrigerator exploring.webp" style="width:100%">
    <img src="/assets/images/comics/beauty parlour.webp" style="width:100%">
    <img src="/assets/images/comics/bonds.webp" style="width:100%">
    <img src="/assets/images/comics/drill guy.webp" style="width:100%">
    <img src="/assets/images/comics/family at temple.webp" style="width:100%">
    <img src="/assets/images/comics/game and popcorn.webp" style="width:100%">
    <img src="/assets/images/comics/geeks.webp" style="width:100%">
    <img src="/assets/images/comics/common sense not so common.webp" style="width:100%" > 
    <img src="/assets/images/comics/crying on bidai.webp" style="width:100%">
    <img src="/assets/images/comics/darwing boundries.webp" style="width:100%">
    <img src="/assets/images/comics/haircut struggle.webp" style="width:100%">
  </div>
  <div class="comiccolumn">
    <img src="/assets/images/comics/waxing day.webp" style="width:100%">
    <img src="/assets/images/comics/working sleeping.webp" style="width:100%">
    <img src="/assets/images/comics/instagram scroll.webp" style="width:100%">
    <img src="/assets/images/comics/khichdi.webp" style="width:100%">
    <img src="/assets/images/comics/lady in saree.webp" style="width:100%">
    <img src="/assets/images/comics/mnc work.webp" style="width:100%">  
    <img src="/assets/images/comics/my brain is in my hands.webp" style="width:100%">
    <img src="/assets/images/comics/nose picking.webp" style="width:100%">
    <img src="/assets/images/comics/puncture guy.webp" style="width:100%">
    <img src="/assets/images/comics/auto riksha.webp" style="width:100%" >
    
  </div>  
  <div class="comiccolumn">
    <img src="/assets/images/comics/sunday aaram 1.webp" style="width:100%">
    <img src="/assets/images/comics/sunday aaram 2.webp" style="width:100%">
    <img src="/assets/images/comics/sunday aaram 3.webp" style="width:100%">
    <img src="/assets/images/comics/talking lady.webp" style="width:100%">
    <img src="/assets/images/comics/ielts.webp" style="width:100%">
    <img src="/assets/images/comics/waiting.webp" style="width:100%">
    <img src="/assets/images/comics/work explode.webp" style="width:100%">
    <img src="/assets/images/comics/helping guy.webp" style="width:100%">
    <img src="/assets/images/comics/work run.webp" style="width:100%">
    <img src="/assets/images/comics/working sleeping 2.webp" style="width:100%">

  </div>  
</div>
   
   <script>
//Get the slider button
const slidesContainer = document.getElementById('slides');
    const slides = document.querySelectorAll('.slide');
    const slider = document.getElementById('slider');
    let currentIndex = 0;

    function updateSlide() {
      const currentSlide = slides[currentIndex];
      const img = currentSlide.querySelector('img');

      // Scroll to the correct image
      slidesContainer.style.transform = `translateX(-${currentSlide.offsetLeft}px)`;

      // Resize the slider box to the image
      slider.style.width = img.offsetWidth + 'px';
      slider.style.height = img.offsetHeight + 'px';
    }

    document.querySelector('.next').addEventListener('click', () => {
      currentIndex = (currentIndex + 1) % slides.length;
      updateSlide();
    });

    document.querySelector('.prev').addEventListener('click', () => {
      currentIndex = (currentIndex - 1 + slides.length) % slides.length;
      updateSlide();
    });

    window.addEventListener('load', updateSlide);
    window.addEventListener('resize', updateSlide);

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
