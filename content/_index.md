---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 Future Career plan'
      subtitle: ''
      text: |-
        
1.Master Python, AI/ML, React.js, and IoT protocols. Learn cloud platforms (AWS, Azure) and mobile app development (Flutter, React Native).
2.Focus on responsive design, performance optimization, and progressive web apps (PWA).
3.Build smart projects integrating IoT and ML. Stay updated with emerging technologies like 5G and edge computing.
4.Obtain credentials in Cybersecurity, AI/ML, and IoT for career advancement.
5.Solve real-world problems through open-source contributions and personal tech projects.
6.Aim for leadership roles or start a tech venture in web development, IoT, or graphics design.
7.Stay current with tech trends, network, and build a personal brand through blogging and public platforms.

    design:
      columns: '1'
  
---
