---
title: Home
slug: /
sections:
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: 'Kylie R Smith, PhD'
      color: text-primary
      styles:
        self:
          textAlign: center
    subtitle: Researcher & Educator
    items:
      - type: FeaturedItem
        title: ''
        tagline: ''
        subtitle: ''
        text: ''
        image:
          type: ImageBlock
          url: /images/Kylie.jpg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
      - type: FeaturedItem
        title: Ko wai au?
        tagline: ''
        subtitle: ''
        text: >+
          Kylie Smith is a researcher and educator with experience teaching in
          primary, secondary and tertiary levels. Her research interests lie in
          democratic education, democratic schooling systems, critical
          pedagogies, student voice, and self-directed learning. Her PhD focused
          on the positive impacts of student participation in secondary school
          systems.

        image:
          type: ImageBlock
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
      - type: FeaturedItem
        title: ''
        tagline: ''
        subtitle: Tēnā koutou katoa.
        text: >
          Ko Aerana me Ingarangi te whakapaparanga mai. Engari, Ko Whitby's toku
          waka. Ko Tāmaki Makauraui te whenua tupu. Nō Te Waipounamu au. Ko
          Takahiwai te kāinga ināianei. 


          Tēnā tātou katoa
        image:
          type: ImageBlock
          url: /images/468525589_10162581618849114_2738407091006045883_n.jpg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
    actions: []
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-16
          - pr-8
        justifyContent: center
      subtitle:
        textAlign: center
  - title: Divider
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title:
      text: ''
      color: text-dark
      type: TitleBlock
    subtitle: You can contact me directly through this form...
    text: |+
      <div style="text-align: left">ORCID ID 0000-0002-3781-6367</div>

    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
          type: TextareaFormControl
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Contact
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
