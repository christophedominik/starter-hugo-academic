widget: slider

active: true

headless: true  # This file represents a page section.

weight = 3

# ... Put Your Section Options Here (section position etc.) ...
Projects

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval: 4000

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height: 300px

item:
  - title: Rice terraces of Batad, Philippines
    content: 'LEGATO'
    # Choose `center`, `left`, or `right` alignment.
    align: left
    # Overlay a color or image (optional).
    #   Deactivate an option by commenting out the line, prefixing it with `#`.
    overlay_color: '#FDFEFE'  # An HTML color value.
    overlay_img: LEGATO_background.png  # Image path relative to your `assets/media/` folder
    overlay_filter: 0.2  # Darken the image. Value in range 0-1.
    # Call to action button (optional).
    #   Activate the button by specifying a URL and button label below.
    #   Deactivate by commenting out parameters, prefixing lines with `#`.
    # cta_label: Download my app
    # cta_url: 'https://example.org'
    # cta_icon_pack: fas
    # cta_icon: graduation-cap
  - title: Pollinators
    content: 'PoshBee'
    align: right
    overlay_color: '#333'
    overlay_img: 'poshbeeback.jpg'
    overlay_filter: 0.2
  - title: Salt-pans of Guérande, France
    content: 'ECOSAL'
    align: left
    overlay_color: '#555'
    overlay_img: 'guerande.png'
    overlay_filter: 0.2
