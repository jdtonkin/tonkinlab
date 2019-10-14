+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 11  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = false

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "500px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "Recent paper in *Nature*"
  content = "To prepare river ecosystems for an uncertain future, we must adapt the way we model and manage them.<br><br>"
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  # overlay_color = "#C28542"  # An HTML color value.
overlay_img = "3gorges-wide.jpg"  # Image path relative to your `static/img/` folder.  
overlay_filter = 0.4  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Get the paper"
  cta_url = "https://doi.org/10.1038/d41586-019-01877-1"
  cta_icon_pack = "far"
  cta_icon = "file-alt"


 [[item]] 
   title = ""
   content = "We argue that we can no longer _solely_ aim to restore river ecosystems to historical states, because often, and increasingly, those states no longer exist. Similarly, models based on past correlations do poorly looking into the future for how species may respond to unprecedented changes."
   align = "center"

  # overlay_color = # "#C28542"  # An HTML color value.
  overlay_img = "horseshoe.jpg"  # Image path relative to your `static/img/` folder.  
  overlay_filter = 0.4  # Darken the image. Value in range 0-1.

 [[item]] 
   title = ""
   content = "We call for rivers to be managed adaptively and for researchers to develop forecasting tools that move beyond simply monitoring the state of ecosystems to establishing the biological mechanisms that underpin their survival."
   align = "center"

  # overlay_color = # "#C28542"  # An HTML color value.
  overlay_img = "stream-wide.jpg"  # Image path relative to your `static/img/` folder.  
  overlay_filter = 0.4  # Darken the image. Value in range 0-1.

+++
