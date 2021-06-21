+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://wowchemy.com/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://wowchemy.com/docs/page-builder/
headless = true  # This file represents a page section.
active = false  # Activate this widget? true/false
weight = 50  # Order that this section will appear.

title = "Methods"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DarkGreen"
  # gradient_end = "ForestGreen"
  
  # Background image.
  # image = "image.jpg"  # Name of image in `static/media/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  # image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  # image_position = "center"  # Options include `left`, `center` (default), or `right`.
  # image_parallax = true  # Use a fun parallax-like fixed background effect? true/false
  
  # Text color (true=light or false=dark).
  # text_color_light = true

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++
The address the research questions, we focus on three different approaches:

1. Using AI and ground control points in the two mountain regions to assess the accuracy of the WTE data for those areas
2. Direct spatial downscaling of the existing 250 m ecosystem map to 30 m using high resolution EO data.
3. Downscaling of the WTE land cover information to generate first a high-resolution land cover map and convert this into a high-resolution ecosystem map following the approach by [Sayre et al. (2020)](https://www.sciencedirect.com/science/article/pii/S2351989419307231?via%3Dihub)

<p align="center">
  <img src="/media/Methods.png">
  <em>Flowchart of the proposed approach to validate and downscale the World Terrestrial Ecosystems product using high-resolution Earth observation data. </em>
</p>