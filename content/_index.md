---
# Leave the homepage title empty to use the site title
title: ""
date: 2024-11-11
type: landing

design:
  # Default section spacing
  spacing: "6rem"
  padding: ["4rem", "4rem", "4rem", "4rem"]  # Top and bottom padding 0, left and right padding 2rem

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: 
      text: ""
      # Show a call-to-action button under your biography? (optional)
    design:
      columns: "1"
      css_class: gray
      background: 
        color: 
        image: 
          # assets/media/debashis.jpg
          # Add your image background to `assets/media/`.
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  

  - block: collection
    id: blog
    content:
      title: Blog Posts
      subtitle: ""
      text: "**Title: My Tech Journey: From Development to IoT Solutions**

       Hi, I’m Debashis Dhali, a 23-year-old Computer Science student at Jahangirnagar University. Starting with frontend development—HTML, CSS, JavaScript, and React—my goal is to become a full-stack developer, hopefully at Google. To get there, I’m following a structured roadmap to deepen my skills across all aspects of web development.

       Beyond coding, I’m diving into IoT with projects aimed at solving local issues. Inspired by Bangladesh’s “More Fish” project, I’m working on a device to monitor water quality in ponds, helping fish farmers increase yields. Another project automates the pre-exam process at my university, reducing time and effort for students through online applications and mobile banking.

       As I grow technically, I’m also committed to self-improvement, focusing on discipline and health. I document my journey through YouTube and blogging, sharing insights as I learn. Each project and challenge brings me closer to my vision of using tech to make a difference!"
      page_type: post
      count: 5
      filters:
        author: "Debashis Dhali"
      order: desc
    design:
      view: date-title-summary
      spacing:
        padding: [0, 0, 0, 0]

  
---
