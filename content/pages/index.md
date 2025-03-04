---
type: PageLayout
title: Home
colors: colors-a
sections:
  - type: HeroSection
    title: "Aspiring Data Scientist|\_ \_ \_ \_ \_ AI & Generative AI Enthusiast"
    subtitle: >-
      Hi, I'm Sujith A C, a passionate Computer Science student specializing in
      Artificial Intelligence and Data Science. I thrive on creating impactful
      solutions using Machine Learning, Data Science, and Generative AI
      technologies. Currently preparing for placements and aiming to become a
      Data Scientist.
    actions: []
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: LabelsSection
    title: Skills
    subtitle: ''
    items:
      - type: Label
        label: 'Programming Languages: Python, Java, C, DSA, R, SQL'
        url: ''
      - type: Label
        label: >-
          Machine Learning & AI: TensorFlow, Scikit-learn, Generative AI, LLM
          Engineering
        url: ''
      - type: Label
        label: >-
          Data Science & Visualization: Jupyter Notebook, SPYDER, Matplotlib,
          Tableau, Power BI
        url: ''
      - type: Label
        label: 'Database Management: MySQL, Database Design and Implementation'
        url: ''
      - type: Label
        label: >-
          Soft Skills: Problem Solving, Team Collaboration, Time Management,
          Adaptability
        url: ''
    colors: colors-f
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
  - type: FeaturedProjectsSection
    subtitle: ''
    actions:
      - type: Link
        label: Explore My Work
        altText: See all projects
        url: /projects
        showIcon: false
        icon: arrowRight
        iconPosition: right
        elementId: ''
    projects:
      - content/pages/projects/project-one.md
      - content/pages/projects/2.md
      - content/pages/projects/3.md
    colors: colors-f
    variant: variant-d
    elementId: ''
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: center
    title: Projects
  - type: FeaturedItemsSection
    title: EXPERIENCES
    items:
      - type: FeaturedItem
        title: INTERNSHIPS
        subtitle: ''
        text: |+
          **Data Science Intern at Cognifyz Technologies**

          *   Created data visualizations using Tableau and Power BI.

          *   Built ML models for classification and regression tasks.

          *   Documented data workflows in Jupyter Notebooks.

          *   Received positive feedback from supervisors.





        actions: []
        elementId: ''
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        title: Projects and Research
        subtitle: ''
        text: >+
          **Machine Learning-Based Predictive Model for Diabetic Nephropathy**


          *   Predicted disease severity using gene polymorphisms and serum
          biomarkers.


          *   Achieved 84.75% accuracy using Random Forest.


          *   Co-authored a research paper with K. Surya Mounika and
          Vivekanandan T.





        actions: []
        elementId: ''
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        title: Hackathons and Competitions
        subtitle: ''
        text: |+
          **Sparkathon (Hackathon) by Walmart**

          *   Worked on the project **REloAD**.



        actions: []
        elementId: ''
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        title: Leadership and Collaboration
        subtitle: ''
        text: >+
          *   **Leadership Role in Student Sports Club**


          *   **Participant in Coding Club and Sports Club at The Apollo
          University**



        elementId: ''
        styles:
          self:
            textAlign: left
    actions: []
    colors: colors-f
    columns: 2
    spacingX: 83
    spacingY: 11
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: TextSection
    colors: colors-f
    variant: variant-a
    title: EDUCATION
    text: |+
      **The Apollo University, Chittoor, Andhra Pradesh, India**

      Bachelor of Technology (B.Tech) in Computer Science and Engineering
      Specialization: Artificial Intelligence and Data Science

      *   **Graduation Date:** 2026

      *   **GPA:** 9.0

    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
  - type: TextSection
    colors: colors-f
    variant: variant-a
    title: '    Certifications'
    subtitle: ''
    text: >+
      *   **Google Cloud Computing Foundations** – Gained foundational knowledge
      of cloud computing services and infrastructure.


      *   **Data Science Intern (Cognifyz Technologies)** – Completed an
      internship focused on data visualization, machine learning model
      development, and data engineering workflows.



    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
  - type: ContactSection
    title: Contact Me
    text: I'm look forward to hearing from you.
    form:
      type: FormBlock
      title: Title of the form
      fields:
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          width: 1/2
          isRequired: 'true'
        - type: EmailFormControl
          name: email
          label: Name
          hideLabel: true
          placeholder: Your email
          width: 1/2
          isRequired: 'true'
        - type: TextareaFormControl
          name: message
          label: Tell me about your project
          hideLabel: true
          placeholder: Tell me about your project
          width: full
          isRequired: true
        - type: CheckboxFormControl
          name: updates
          label: Sign me up to receive updates
          width: full
          isRequired: 'false'
      submitLabel: Send Message
      elementId: contact-form
      styles:
        submitLabel:
          textAlign: left
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: center
      text:
        textAlign: center
  - type: ContactSection
    title: Contact Me
    text: I'm look forward to hearing from you.
    form:
      type: FormBlock
      title: Title of the form
      fields:
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: false
          placeholder: Your name
          width: 1/2
          isRequired: 'true'
        - type: EmailFormControl
          name: email
          label: Name
          hideLabel: false
          placeholder: Your email
          width: 1/2
          isRequired: 'true'
        - type: TextareaFormControl
          name: message
          label: Tell me about your project
          hideLabel: true
          placeholder: Tell me about your project
          width: full
          isRequired: true
        - type: CheckboxFormControl
          name: updates
          label: Sign me up to receive updates
          width: full
          isRequired: 'false'
      submitLabel: Send Message
      elementId: contact-form
      styles:
        submitLabel:
          textAlign: left
    media:
      type: ImageBlock
      url: /images/contact.jpg
      altText: Contact form image
      caption: Caption of the image
      elementId: ''
    colors: colors-d
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
backgroundImage:
  type: BackgroundImage
  url: /images/bg2.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 41
---
