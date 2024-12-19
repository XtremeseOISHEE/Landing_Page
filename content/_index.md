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
      secondary_action:
        text: Read the docs
        url: https://docs.hugoblox.com
      announcement:
        text: "Explore our latest digital solutions to boost your business!"
        link:
          text: "Discover More"
          url: "/blog/"
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
        - statistic: "1k+"
          description: |
            Websites built  
            with Mav Chase
        - statistic: "10k+"
          description: |
            Users Around
            The World
        - statistic: "3k+"
          description: |
            Discord community  
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
      title: Features
      text: Our experise
      items:
        - name: Digital Marketing
          icon: magnifying-glass
          description: Strategies to grow your online presence and reach your audience effectively.
        - name: Web Development
          icon: bolt
          description: Creating responsive and dynamic websites tailored to your needs.
        - name: Custom Software
          icon: code-bracket 
          description: Developing software solutions customized for your business requirements.
        - name: Custom Notion template
          icon: sparkles
          description: Designing personalized Notion templates to organize and streamline workflows.
        - name: Branding
          icon: star
          description: Building a unique and memorable identity for your business.
        - name: Video Editing
          icon: rectangle-group
          description: Crafting professional-quality videos for marketing or personal use.
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Build your future-proof website
          text: As easy as 1, 2, 3!
          feature_icon: check
          features:
            - "Future-proof - edit your content in text files"
            - "Website built by our professionals"
            - "No coding knowledge required"
          # Upload image to `assets/media/` and reference the filename here
          image: build-website.png
          button:
            text: Get Started
            url: https://hugoblox.com/templates/
        # - title: Large Community
        #   text: Join our large community on Discord - ask questions and get live responses
        #   feature_icon: bolt
        #   features:
        #     - "Dedicated support channel"
        #     - "3,000+ users on Discord"
        #     - "Share your site and get feedback"
        #   # Upload image to `assets/media/` and reference the filename here
        #   image: coffee.jpg
        #   button:
        #     text: Join Discord
        #     url: https://discord.gg/z8wNYzb
  #   design:
  #     # Section background color (CSS class)
  #     css_class: "bg-gray-100 dark:bg-gray-900"
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
  #     title: Build your future-proof website
  #     text: As easy as 1, 2, 3!
  #     button:
  #       text: Get Started
  #       url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
