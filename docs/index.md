---
layout: default
title: Home
---
<section id="hero">
    <h1>Welcome to My Website</h1>
    <p>I am Sophia Epstein, a PhD student and researcher.</p>
</section>

<section id="home">
  <h2>Welcome</h2>
  <div class="bio-section">
    <img src="https://oden.utexas.edu/media/directory-assets/profile-imgs/Sophia_Epstein.png" alt="Sophia Epstein" class="bio-image">
    <p class="bio-text">I am currently pursuing my PhD at the Oden Institute, University of Texas at Austin. I obtained my BA in Applied Mathematics and Neuroscience in 2022 from Claremont McKenna College with a specialization in computational models of neural processes under John Milton.</p>
  </div>
</section>

<script>
    window.addEventListener("scroll", function() {
        const heroSection = document.getElementById("hero");
        heroSection.style.opacity = 1 - window.scrollY / window.innerHeight;
        
        // If you want to completely remove it from view after scrolling a certain distance
        if (window.scrollY > window.innerHeight) {
            heroSection.style.display = 'none';
        } else {
            heroSection.style.display = 'block';
        }
    });
</script>


