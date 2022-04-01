---
widget: slider  # Use the Slider widget as this page section
weight: 30  # Position of this section on the page
active: true  # Publish this section?
headless: true  # This file represents a page section.

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: '300px'
  is_fullscreen: false
  # Automatically transition through slides?
  loop: true
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: Volmeter for Research
      content: 
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        # media: coders.jpg
      link:
        # icon: graduation-cap
        # icon_pack: fas
        text: Learn more
        url: ../research/
    - title: Volmeter for Health and Sport
      content:
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        # media: coders.jpg
      link:
        text: Learn more
        url: ../health/
    - title: Team
      content: Talented scientists, engineers, and specialists in biophysics and muscle health assessment
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        # media: coders.jpg
      link:
        text: View team
        url: ../team/

---