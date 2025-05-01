---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: PATRICIO GARZON
      color: text-dark
      type: TitleBlock
    subtitle: Software Engineer
    text: >+
      Hi, I'm a Software Engineer specializing in C++ and High-Performance UI/UX
      Development.

    actions:
      - label: More About me
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
      - label: Projects
        altText: ''
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Link
    media:
      url: /images/IntroImage.png
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: ''
      color: text-light
      type: Badge
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
  - type: FeaturedItemsSection
    title:
      text: Designing code with purpose.
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: 'Expertise Development in:'
    items:
      - type: FeaturedItem
        title: Video Games
        subtitle: Development
        text: >+
          With over 4 years experience with Unreal Engine/Unity combined with
          C++/C#. I am proud to deliver quality projects

        actions: []
        elementId: null
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
        image:
          type: ImageBlock
          altText: Lightning bolt symbol on red background
          elementId: ''
          styles:
            self:
              borderRadius: x-large
      - title: Mobile & App
        subtitle: Development
        text: "Working with Android and IOS has been one of my top experiences in my software Engineer Career.\_\n\n"
        image:
          altText: Featured icon two
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            textAlign: left
            justifyContent: center
        type: FeaturedItem
      - title: Software
        subtitle: Development
        text: >
          With 4 years of experience in building scalable applications. I excel
          at solving complex problems, optimizing performance, and delivering
          impactful user-focused software.
        image:
          altText: Featured icon three
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
        type: FeaturedItem
    actions:
      - label: Get started
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
    badge:
      label: ''
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - subtitle: Software & Languages
    images:
      - url: /images/Python-Logo.png
        altText: PythonLogo
        type: ImageBlock
      - altText: Vise logo
        type: ImageBlock
      - url: /images/Xcode-Logo.png
        altText: XCode Logo
        type: ImageBlock
      - url: /images/VisualStudio-Logo.png
        altText: Visual Studio Logo
        type: ImageBlock
      - url: /images/UnityLogo.png
        altText: Unity Logo
        type: ImageBlock
      - altText: 'Unreal Engine '
        type: ImageBlock
        url: /images/Unreal-removebg-preview_resized.png
      - url: /images/Javascript-Logo_resized.png
        altText: 'Javascript '
        type: ImageBlock
    motion: move-to-left
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: ImageGallerySection
  - posts:
      - content/pages/blog/case-study-1.md
      - content/pages/blog/case-study-3.md
      - content/pages/blog/case-study-2.md
    showThumbnail: true
    showDate: true
    showAuthor: true
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
    type: FeaturedPostsSection
    hoverEffect: move-up
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
