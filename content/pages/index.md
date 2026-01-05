---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: "Hi, I’m Yashpreet Kamboj, a B.Tech Computer Science & Engineering student with a strong interest in\_ programming, robotics, and problem-solving"
    subtitle: >-
      My journey with technology started in school, where I actively worked on
      robotics projects, algorithms, and competitive tech events. I enjoy
      learning continuously and experimenting with new tools and libraries
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        flexDirection: row-reverse
        textAlign: left
    type: HeroSection
    actions: []
  - type: TextSection
    title: 🎓 Education
    text: |+


      *   **B.Tech in Computer Science & Engineering**
          *Uttaranchal University, Dehradun (UK)*
          **Batch:** 2024 – Present

      *   \*   **Class XII (CBSE)** – 71.8%
          *The Genius School, Rania, Sirsa (HR)* | 2024

      *   \*   **Class X (CBSE)** – 85.8%
          *The Genius School, Rania, Sirsa (HR)* | 2022

    colors: colors-f
    variant: variant-a
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
        textAlign: left
  - type: FeaturedItemsSection
    title: 💼 Experience
    items:
      - type: FeaturedItem
        title: 🔹 Artificial Intelligence Intern
        subtitle: Coding Junior
        text: >+


          *   Worked on fundamentals of **Artificial Intelligence**


          *   Gained hands-on experience with AI concepts and basic
          implementations


          *   Improved problem-solving and logical thinking through guided
          projects

        actions: []
        elementId: ''
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        title: 🔹 Google Student Ambassador (Present)
        subtitle: Google
        text: >+


          *   Representing Google at the student level


          *   Promoting Google programs, technologies, and learning initiatives


          *   Engaging with students through tech awareness and community
          activities

        actions: []
        elementId: ''
        styles:
          self:
            textAlign: left
    actions: []
    colors: colors-f
    columns: 1
    spacingX: 16
    spacingY: 16
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
        textAlign: left
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: Got an interesting project? Tell me more...💬
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: 1/2
          type: EmailFormControl
        - name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: updatesConsent
          label: Sign me up to recieve updates
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: Submit 🚀
      styles:
        self:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        flexDirection: row
        textAlign: left
---
