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
        url: uploads/Kevin Cashman, CV.pdf
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
      title: 'Academic Publications (Selected)'
      subtitle: ''
      text: |-
       + [How effective was assistance to the vulnerable countries during the pandemic? Comparing the Debt Service Suspension Initiative and Special Drawing Rights](http://dx.doi.org/10.61801/OUAESS.2023.1.19), with Lara Merling, in *Ovidius University Annals, Economic Sciences Series*
        
       
       + [Special Drawing Rights: The right tool to use to respond to the pandemic and other challenges](https://doi.org/10.1080/05775132.2022.2134638), with coauthors, in *Challenge* 
       
       + [Book review: Darrell M. West, The Future of Work: Robots, AI, and Automation](https://doi.org/10.4337/roke.2020.01.11) in *Review of Keynesian Economics*
       
       + [What Happened in Bolivia’s 2019 Vote Count?](https://doi.org/10.1080/05775132.2020.1711490), with coauthors, in *Challenge*
    design:
      columns: '1'
  - block: markdown
    content:
      title: 'Policy Reports (Selected)'
      subtitle: ''
      text: |-
       + [Special Drawing Rights one year later: By the numbers](https://cepr.net/special-drawing-rights-one-year-later-by-the-numbers/), with Andrés Arauz, Center for Economic and Policy Research (CEPR)
       
       + [Special Drawing Rights could help recover millions of export-related US jobs, and create even more](https://cepr.net/report/special-drawing-rights-could-help-recover-millions-of-export-related-us-jobs-and-create-even-more/), CEPR
       
       + [Republican Senate leadership on IMF Special Drawing Rights (SDRs): A fact check](https://cepr.net/report/republican-senate-leadership-on-imf-special-drawing-rights-sdrs-a-fact-check/), with Mark Weisbrot, CEPR
       
       + [Stick shift: Autonomous vehicles, driving jobs, and the future of work](https://www.law.gwu.edu/sites/g/files/zaxdzs5421/files/downloads/Stick-Shift-Autonomous-Vehicles-Driving-Jobs-and-the-Future-of-Work.pdf), with coauthors, Center for Global Policy Solutions
       
       + [Life after debt in Puerto Rico: How many more lost decades?](https://cepr.net/report/life-after-debt-in-puerto-rico-how-many-more-lost-decades/), with coauthors, CEPR
    design:
      columns: '1'
  - block: markdown
    content:
      title: 'Editorials (Selected)'
      subtitle: ''
      text: |-
       + [Biden price hike? The nexus of foreign policy and economic crisis](https://responsiblestatecraft.org/2022/07/26/biden-price-hike-the-nexus-of-foreign-policy-and-economic-crisis/), *Responsible Statecraft*          
       
       + [A week after the coup in Bolivia, there's still no proof of electoral fraud](https://jacobin.com/2019/11/evo-morales-bolivia-coup-election-fraud-organization-of-american-states),*Jacobin* 
       
       + [US sanctions are designed to kill](https://jacobin.com/2019/09/us-iran-sanctions-donald-trump-iran-deal-oil-banks), with Cavan Kharrazian, *Jacobin* 
       
       + [There is no alternative to managing the economy and the climate](https://mronline.org/2019/05/16/there-is-no-alternative-to-managing-the-economy-and-the-climate/), *MR Online* 
       
       + [Social Security trustees consistently agree: The program is well-funded](https://www.commondreams.org/views/2019/05/06/social-security-trustees-consistently-agree-program-well-funded), with Adewale Maye, *Common Dreams* 
       
       + [Don’t be afraid of robots: Technology is what we make of it](https://www.nakedcapitalism.com/2017/11/dont-afraid-robots-technology-make.html), *Naked Capitalism*
       
       + [Cities need more public transit, not more Uber and self-driving cars](https://billmoyers.com/story/cities-need-public-transit-not-uber-self-driving-cars/), *BillMoyers.com*
    design:
      columns: '1'
  #- block: collection
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
  #- block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  #- block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
  #- block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  #- block: cta-card
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
