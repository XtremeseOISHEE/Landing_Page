---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Crafting Excellence Through Customized Solutions
      text:  EASY. FREE (OPEN SOURCE). NO-CODE  
      primary_action:
        text: Get Started
        url: https://hugoblox.com/templates/
        icon: rocket-launch
      # secondary_action:
      #   text: Read the docs
      #   url: https://docs.hugoblox.com
      announcement:
        text: "Explore our latest digital solutions to boost your business!"
        link:
          text: "Discover More"
          url: "/portfolio/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: bg-triangles.svg
          filters:
            brightness: 0.5
  - block: stats
    content:
      items:
        - statistic: "150+"
          description: |
            Websites built  
            with Mav Chase
        - statistic: "100+"
          description: |
            Users Around
            The World
        - statistic: "500+"
          description: |
            facebook community  
            for support
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: features
    content:
      title: Services
      text: Our experise
      items:
        - name: <a href="/Digital" target="_blank">Digital Marketing</a>
          icon: magnifying-glass
          description: Strategies to grow your online presence and reach your audience effectively.
        - name: <a href="/web" target="_blank">Web Development</a>
          icon: bolt
          description: Creating responsive and dynamic websites tailored to your needs.
        - name: <a href="/custom" target="_blank">Custom Software</a>
          icon: code-bracket 
          description: Developing software solutions customized for your business requirements.
        - name: <a href="/notion" target="_blank">Custom Notion template</a>
          icon: sparkles
          description: Designing personalized Notion templates to organize and streamline workflows.
        - name: <a href="/branding" target="_blank">Branding</a>
          icon: star
          description: Building a unique and memorable identity for your business.
        - name: <a href="/video" target="_blank">Video Editing</a>
          icon: rectangle-group
          description: Crafting professional-quality videos for marketing or personal use.
        - name: <a href="/social" target="_blank">Social Media Marketing Strategy</a>
          icon: bolt
          description: Enhance your online presence.

  # - block: cta-image-paragraph
  #   id: about
  #   content:
  #     title: About Us
  #     text: |
  #       At [Your Company Name], we specialize in delivering cutting-edge digital solutions tailored to your business needs.  
  #       Our mission is to empower businesses by providing tools and strategies that make a difference.  
  #       From branding to custom software, our experienced team ensures excellence in every project.  
  #     features:
        # - "Experience: Over 5 years in the industry"
        # - "Global Reach: Clients in 20+ countries"
        # - "Commitment: Dedicated to innovation and quality"
  #   design:
  #     css_class: "bg-gray-200 dark:bg-gray-800"
  #     spacing:
  #       padding: ["3rem", 0, "3rem", 0]
  
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: About Us
          text: At Mav Chase, we specialize in redefining digital excellence with innovative solutions tailored to meet your business needs. Our mission is to empower brands with cutting-edge strategies and tools, helping them scale, succeed, and lead in their respective industries. From branding to custom software, our dedicated team brings expertise, creativity, and a commitment to excellence in every project we undertake.
          feature_icon: check
          features:
            - "Experience: Over 5 years of crafting impactful digital solutions"
            - "Global Reach: Successfully serving clients in 15+ countries"
            - "Innovation: Focused on delivering trendsetting ideas and technology"
            - "ROI Focus: Strategies designed to ensure measurable success"
            - "Agility: Dynamic services customized to your unique goals"
          # journey:
          # title: Our Journey
          # milestones:
          #   - "2024: Recognized as a leading name in delivering tailored business solutions."
        # Upload image to `assets/media/` and reference the filename here
          # Upload image to `assets/media/` and reference the filename here
          image: build.jpg
          # button:
          #   text: Get Started
          #   url: https://hugoblox.com/templates/
            
        - title: Build your future-proof website
          text: With our professionals!
          feature_icon: check
          features:
            - "Future-proof - edit your content in text files"
            - "Website built by our professionals"
            - "Clients won't need coding knowledge required"
          # Upload image to `assets/media/` and reference the filename here
          image: time.jpg
          button:
            text: Get Started
            url: /web
        - title: Custom-Made Notion tamplate
          text: Streamline your workflow with tailored Notion templates for ultimate productivity.
          feature_icon: bolt
          features:
            - "Transform your productivity with tailored solutions"
            - "Premium templates designed for businesses, teams, and individuals"
            - "Take your workflow to the next level with efficiency and customization"
          # Upload image to `assets/media/` and reference the filename here
          image: notion.jpg
          button:
            text: We build for you
            url: /notion
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  # - block: testimonials
  #   content:
  #     title: ""
  #     text: ""
  #     items:
  #       - name: "Hugo Smith"
  #         role: "Marketing Executive at X"
  #         # Upload image to `assets/media/` and reference the filename here
  #         image: "testimonial-1.jpg"
  #         text: "Awesome, so easy to use and saved me so much work with the swappable pre-designed sections!"
  #   design:
  #     spacing:
  #       # Reduce bottom spacing so the testimonial appears vertically centered between sections
  #       padding: ["6rem", 0, 0, 0]
  # - block: cta-card
  #   content:
  #     title: About Us
  #     text: |
  #       At Mav Chase, we specialize in delivering cutting-edge digital solutions tailored to your business needs.  
  #       Our mission is to empower businesses by providing tools and strategies that make a difference.  
  #       From branding to custom software, our experienced team ensures excellence in every project.  
  #     # button:
  #     #   text: Get Started
  #     #   url: https://hugoblox.com/templates/
  #     features:
  #       - "Experience: Over 5 years in the industry"
  #       - "Global Reach: Clients in 20+ countries"
  #       - "Commitment: Dedicated to innovation and quality"
  #   design:
  #     card:
  #       # Card background color (CSS class)
  #       css_class: "bg-primary-700"
  #       css_style: ""
---
