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
      # button:
        # text: Download CV
        # url: uploads/resume.pdf
    design:
      css_class: bright
      # background:
        # color: beige
        # image:
          # Add your image background to `assets/media/`.
          # filename: stacked-peaks.svg
          # filters:
            # brightness: 1.0
          # size: cover
          # position: center
          # parallax: false
  # - block: markdown
    # content:
      # title: '📚 My Research'
      # subtitle: ''
      # text: |-
        # Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

        # I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.
        
        # Please reach out to collaborate 😃
    # design:
      # columns: '1'
  - block: markdown
    content:
      title: 'Experience'
      subtitle: ''
      text: |- 
        Nov 2022 – **_Present_**  
        Teaching Assistant  
        Department of Computer Engineering  
        College of Computer and Information Sciences  
        King Saud University  
        Riyadh, Riyadh, Saudi Arabia    
        {style="font-size:0.8em; color:black"}    
        <br/>

        June 2022 – Dec 2022  
        Research Engineer  
        Visual Computing Center (Peter Wonka Research Group)  
        Computer, Electrical and Mathematical Science and Engineering Division  
        King Abdullah University of Science and Technology (KAUST)  
        Mecca, Thuwal, Saudi Arabia  
        {style="font-size:0.8em; color:black"} 
        <br/>

        Aug 2021 – Oct 2022  
        Artificial Intelligence Engineer  
        Research and Development Department  
        National Center for Artificial Intelligence (NCAI/SDAIA)  
        Riyadh, Riyadh, Saudi Arabia  
        {style="font-size:0.8em; color:black"}   
        <br/>

        Nov 2020 – July 2021  
        Deep Learning Software Developer  
        Imaging Research Department  
        King Abdullah International Medical Research Center (KAIMRC/KSAU-HS)  
        Riyadh, Riyadh, Saudi Arabia  
        {style="font-size:0.8em; color:black"} 
    # spacing: 
      # padding: [0, 0, 20px, 0]
    design:
      background:
        color: WhiteSmoke
      columns: '1'
  # - block: collection
    # id: papers
    # content:
      # title: Featured Publications
      # filters:
        # folders:
          # - publication
        # featured_only: true
    # design:
      # view: article-grid
      # columns: 2
  # - block: collection
    # id: news
    # content:
      # title: Awards
      # subtitle: ''
      # text: ''
      # Page type to display. E.g. post, talk, publication...   this is a comment 
      # page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      # count: 5
      # Filter on criteria    this is a comment
      # filters:
        # author: ""
        # category: ""
        # tag: ""
        # exclude_featured: false
        # exclude_future: false
        # exclude_past: false
        # publication_type: ""
      # Choose how many pages you would like to offset by    
      # offset: 0
      # Page order: descending (desc) or ascending (asc) date.    
      # order: desc
    # design:
      # Choose a layout view
      # view: date-title-summary
      # background: 
        # color: slate
      # Reduce spacing
      # spacing: 
        # padding: [40px, 0, 20px, 0]
  # - block: collection
  #   content:
  #     title: Experience
  #     text: ""
  #     filters:
  #       folders:
  #         - exp
  #       exclude_featured: true
  #   design:
  #     view: citation
  #     background:
  #       color: offwhite
  #     # Reduce spacing
  #     spacing: 
  #       padding: [40px, 0, 20px, 0]
  - block: collection
    content:
      title: Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      view: citation
      background:
        color: offwhite
      # Reduce spacing
      # spacing: 
        # padding: [0, 0, 20px, 0]
  - block: markdown
    content:
      title: 'Features Projects'
      subtitle: ''
      text: |- 
         Learning Robust and Explainable Representation for Rare Disease Diagnosis From Facial Images      
         Feb 2023 – July 2023     
         {style="font-size:0.8em; color:black"}  
         <br/>
         
         Multi-supervised Deep Framework for Robust Automatic Cellular Anomaly Recognition  
         Dec 2022 – May 2023   
         {style="font-size:0.8em; color:black"}  
         <br/>  

         Domain Generalization: Data Acquisition/Population Agnostic Model Via Features Disentanglement  
         June 2022 – Dec 2022  
         {style="font-size:0.8em; color:black"}  
         <br/>

         Diabetic Retinopathy Detection  
         Aug 2021 – June 2022  
         {style="font-size:0.8em; color:black"}  
         <br/>

         Unconstrained Face Recognition: Proposing a Novel Loss Function  
         Sep 2021 – Oct 2022  
         {style="font-size:0.8em; color:black"}  
         <br/>

         Knowledge Graph Representation for Drugs and Genes Interactions  
         Dec 2021 – Feb 2022  
         {style="font-size:0.8em; color:black"}  
         <br/>

         Peripapillary Atrophy (PPA) Detection In Fundus Images Using Deep Learning  
         Nov 2020 – July 2021  
         {style="font-size:0.8em; color:black"}  
         <br/>

         Detecting Abnormal Traffic Patterns in an IoT Tracking System  
         Nov 2019 – Sep 2020  
         {style="font-size:0.8em; color:black"}  
         <br/>

         Handwritten Arabic Signatures Recognition  
         Feb 2020 – Aug 2020  
          {style="font-size:0.8em; color:black"}  
         
    # spacing: 
      # padding: [0, 0, 20px, 0]
    design:
      background:
        color: WhiteSmoke
      columns: '1'
  # - block: collection
    # id: talks
    # content:
      # title: Recent & Upcoming Talks
      # filters:
        # folders:
          # - event
    # design:
      # view: article-grid
      # columns: 1
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

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
