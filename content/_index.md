---
title: 'Главная'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Оптимизируй свою систему вместе с LLM-INTEGRATION 
      text: 🧱 ПРОСТО. СВОБОДНО. БЕЗ ТРУДНОСТЕЙ 🧱
      primary_action:
        text: Начать
        url: https://hugoblox.com/templates/
        icon: rocket-launch
      secondary_action:
        text: Read the docs
        url: https://docs.hugoblox.com
      announcement:
        text: "Новая версия интерфейса на подходе"
        link:
          text: "Read more"
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
        - statistic: "1M+"
          description: |
            Websites built  
            with Hugo Blox
        - statistic: "10k+"
          description: |
            GitHub stars  
            since 2016
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
      text: Build your site with blocks 🧱
      items:
        - name: Оптимизация CRM
          icon: magnifying-glass
          description: Оптимизируйте систему под ваши потребности
        - name: Быстрые решения
          icon: bolt
          description: Быстрое создание софта
        - name: Просто в использовании
          icon: sparkles
          description: Используйте систему без заморочек
        - name: Возможность проф. роста
          icon: code-bracket
          description: Теперь не нужно тратить время на бесполезную рутину
        - name: Высокая продуктивность сотрудников
          icon: star
          description: Ваши сотрудники скажут вам "Спасибо"
        - name: Удобство использования
          icon: rectangle-group
          description: Используйте систему удобно
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Оптимизируйте вашу систему
          text: 1, 2, 3!
          feature_icon: check
          features:
            - "LLM-INTERGTATION - компания будущего для развития CRM систем в сторону AI-оптимизации"
            - "Сохранение вашего бюджета за счет сокращения штата"
            - "Теперь никаких сложностей с сотрудниками!"
          # Upload image to `assets/media/` and reference the filename here
          image: build-website.png
          button:
            text: Узнать больше
            url: https://hugoblox.com/templates/
        - title: Контроль
          text: Вы сможете контролировать своих аналитиков, так как система проста!
          feature_icon: bolt
          features:
            - "Система блочных структур"
            - "3,000+ пользователей"
            - "Организуй пространство с комфортом"
          # Upload image to `assets/media/` and reference the filename here
          image: coffee.jpg
          button:
            text: Присоединиться
            url: https://discord.gg/z8wNYzb
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "Мария Иванова"
          role: "Маркетолог компании МДМ-СИСТЕМС"
          # Upload image to `assets/media/` and reference the filename here
          image: "testimonial-1.jpg"
          text: "Моя компания расцвела с приходом в неё LLM-INTEGRATION"
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
  - block: cta-card
    content:
      title: Построй систему мечты вместе с нами!
      text: Просто, как  1, 2, 3!
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
