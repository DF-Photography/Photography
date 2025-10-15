<html>
  <head>
    <title>my website</title>
    <style>
      .gallery {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-evenly;
        gap: 10px;
        padding: 10px;
      }
      .gallery img {
        width: 48%;
        height: auto;
        border-radius: 8px;
        box-shadow: 0 2px 6px rgba(0,0,0,0.2);
      }
      @media (max-width: 600px) {
        .gallery img {
          width: 100%;
        }
      }
    </style>
  </head>
  <body>
    <h1>My Photography Website</h1>
    <hr>
    <h3>About Me</h3>
    <p>My name is David Fernandez. I recently started photography as a hobby. I took a photography class in college and I while I am not aiming for a career in photography I do want to improve my skills.</p>
    <hr>
    <h3>My Best Photographs</h3>
    <div class="gallery">
      <img src="Best/IMG_1256_Best.jpg" loading="lazy" alt="Project 9">
      <img src="Best/IMG_1149_Best.jpg" loading="lazy" alt="Project 8">
      <img src="Best/IMG_0907_Best.jpg" loading="lazy" alt="Project 7">
      <img src="Best/IMG_0850_Best.jpg" loading="lazy" alt="Project 6">
      <img src="Best/IMG_0801_Best.jpg" loading="lazy" alt="Project 5">
      <img src="Best/IMG_0752_Best.jpg" loading="lazy" alt="Project 4">
      <img src="Best/IMG_0660_Best.jpg" loading="lazy" alt="Project 3">
      <img src="Best/IMG_0550_Best.jpg" loading="lazy" alt="Project 2">
      <a href="Project1.html">
      <img src="Best/IMG_0488_Best.jpg" loading="lazy" alt="Project 1">
      </a>
    </div>
  </body>
</html>
