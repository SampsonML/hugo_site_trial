---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: markdown
    content:
      text: >
        <div id="boot-screen">
          <p class="boot-line" style="--delay: 0s;">&gt; booting system...<span 
          class="cursor">▊</span></p>
          <p class="boot-line" style="--delay: 1.2s;">&gt; loading user information k<span 
          class="cursor">▊</span></p>
        </div>
        <script>
          document.body.classList.add("loading");
          setTimeout(() => {
            const boot = document.getElementById("boot-screen");
            if (boot) boot.style.display = "none";
            document.body.classList.remove("loading");
          }, 3800);
        </script>

  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      # button:
      #  text: cv
      #  url: uploads/AcademicCVSampsonMatt.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename:  wallpaper_website5.png 
          filters:
            brightness: 0.01
          size: cover
          position: center
          parallax: true

  - block: markdown
    content:
      text: ""
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename:  wallpaper_website5.png
          filters:
            brightness: 0.01
          size: cover
          position: center
          parallax: true

  - block: markdown
    content:
      text: ""
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename:  wallpaper_website5.png 
          filters:
            brightness: 0.01
          size: cover
          position: center
          parallax: true

  - block: markdown
    content:
      text: ""
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename:  wallpaper_website5.png 
          filters:
            brightness: 0.01
          size: cover
          position: center
          parallax: true

  - block: markdown
    content:
      text: ""
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename:  wallpaper_website5.png 
          filters:
            brightness: 0.01
          size: cover
          position: center
          parallax: true
---
