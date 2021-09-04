---
widget: slider
headless: true  # This file represents a page section.
active: false
weight: 30

# ... Put Your Section Options Here (section position etc.) ...

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval: false

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height: "calc(85vh)"


item:
  - title: Carbon Footprint of Medical Conferences
    content: Examining the American Psychiatric Association
    # Choose `center`, `left`, or `right` alignment.
    align: right
    # Overlay a color or image (optional).
    #   Deactivate an option by commenting out the line, prefixing it with `#`.
    # overlay_color: '#666'  # An HTML color value.
    overlay_img: headers/RegionalFL-NL.jpg  # Image path relative to your `assets/media/` folder
    # overlay_filter: 0.5  # Darken the image. Value in range 0-1.
    # Call to action button (optional).
    #   Activate the button by specifying a URL and button label below.
    #   Deactivate by commenting out parameters, prefixing lines with `#`.
    cta_label: JAMA Article
    cta_url: 'https://doi.org/10.1001/jamanetworkopen.2020.35641'
    cta_icon_pack: fas
    cta_icon: book-open

  - title: Migration and Mobility
    content: How do migrant remittances affect inequality?
    align: left
    overlay_img: headers/mobility.png
    overlay_filter: 0.5
    cta_label: Undergraduate Thesis
    cta_url: https://www.researchgate.net/publication/349605494_Domestic_Remittance_in_China_Rural-Urban_Migration's_Trail_of_Inequality
    cta_icon_pack: fas
    cta_icon: graduation-cap

  - title: blocklength
    content: My first R package - v0.1.4 published to CRAN!
    align: left
    overlay_img: headers/blocklength.png
    cta_label: "Package Website"
    cta_url: "https://alecstashevsky.com/r/blocklength"

    
    
    
---
