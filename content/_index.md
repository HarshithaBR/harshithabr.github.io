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
  # - block: markdown
  #   content:
  #     title: '📚 My Research'
  #     subtitle: 'SLURM'
  #     text: |-
  #       - Working at Sensing, Learning, and Understanding for Robotic Manipulation (SLURM) Lab at University of Southern California (USC) on Caregiving Robots, Plant Manipulation
  #       - Working on robotic manipulation in contact rich scenarios and leveraging trajectory optimisation for planning.
  #       - Building a simulation for scooping particular particles in a clustered environment.
  #       - Building a solution to enable robotic assistance for dressing of patients with muscular dystrophe and other neuro immune conditions
  #     subtitle: 'Indian Institue of Science'
  #     text: |-
  #       - Worked at Intelligent Inclusive Interaction Design (I3D) Lab, CPDM, Indian Institute of Science, Bangalore
  #       - Performed a Comparative study across Mixed reality and Virtual reality based remote welding Digital twin applications and mapping the coordinates defined for welding movement to the robot coordinates using regression technique.
  #       - Built an assistive Assembly Process Instruction tool in collaboration with Collin's Aerospace, where Computer Vision is used to detect the components. Involved extensively in this stage of the project, which enabled me to understand various types of object detection algorithms in Computer Vision, study various object detection models(YOLO V5, YOLO V7, DETR, YOLOV8) and different versions of the same. Instructions and warnings based on a defined Assembly Process are provided to the user in a mixed reality application; after the detection of the components.
  #       - Built a custom dataset for the components in hand and got experience in the various pre-processing steps involved with creating the dataset, with real and synthetic images. Tried different augmentations on the dataset created.   
  #       - Worked on analysing and comparing different anchoring techniques to handle the swimming effect of Holograms in a mixed reality application built for Hololens.
  #       - Developed a semantic segmentation model designed for robust object detection in complex and unstructured environments, critical for improving autonomous system safety and efficiency. A dynamic fusion mechanism based on confidence scores allows adaptive performance in changing conditions. Evaluated on the Indian Driving Dataset (IDD) and the Cityscape dataset, the model surpasses four state-of-the-art methods, achieving 12.91% and 19.7% better F1 scores, respectively. 
  #   design:
  #     columns: '1'

  - block: markdown
    content:
      title: '📚 My Research'
      text: |-
        SLURM Lab, USC
        - Working at Sensing, Learning, and Understanding for Robotic Manipulation (SLURM) Lab at University of Southern California (USC) on Caregiving Robots, Plant Manipulation.
        - Working on robotic manipulation in contact-rich scenarios and leveraging trajectory optimization for planning.
        - Building a simulation for scooping particular particles in a clustered environment.
        - Building a solution to enable robotic assistance for dressing patients with muscular dystrophy and other neuro-immune conditions, as well as working on assistance for sponge bathing a patient to ensure maximum coverage.

        I3D Lab, Indian Institute of Science, Bangalore
        - Worked at Intelligent Inclusive Interaction Design (I3D) Lab, CPDM, Indian Institute of Science, Bangalore.
        - Performed a comparative study across Mixed Reality and Virtual Reality-based remote welding Digital Twin applications and mapped the coordinates defined for welding movement to the robot coordinates using a regression technique.
        - Built an assistive Assembly Process Instruction tool in collaboration with Collins Aerospace, where Computer Vision is used to detect the components. 
        - Built a custom dataset for the components in hand and gained experience in the various pre-processing steps involved with creating the dataset, using both real and synthetic images. Tried different augmentations on the dataset created.
    design:
      columns: '1'


  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     view: article-grid
  #     columns: 1
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: dark; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!
        
        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
