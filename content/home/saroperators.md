+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://wowchemy.com/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://wowchemy.com/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 20  # Order that this section will appear.

title = "SAR Operators"
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
SAR2Cube has built-in processes for basic and advanced SAR operators, accessible using the openEO API. The current implemented SAR operators are the following:
<style>
.column {
  float: left;
  width: 50%;
  padding: 10px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
img.medium {
  max-width: 500px;
}
</style>
<div class="row">
    <div class="column" align="left">
      <div class="row"><h2>Spatial subsetting</h2></div>
    </div>
    <div class="column" align="center">
      <img class="medium" src="/media/spatial_subset.png">
      <em>The selected area of Bolzano in slant-range.</em>
    </div>
</div>
<div class="row">
    <div class="column" align="left">
      <div class="row"><h2>Amplitude/Intensity</h2></div>
    </div>
    <div class="column" align="center">
      <img class="medium" src="/media/amplitude_intensity.png">
      <em>Amplitude and Intensity over South Tyrol.</em>
    </div>
</div>
<div class="row">
    <div class="column" align="left">
      <div class="row"><h2>Interferometric Coherence</h2></div>
    </div>
    <div class="column" align="center">
      <img class="medium" src="/media/VV_coh_4x19.png">
      <em>6-days VV Coherence over South-Tyrol.</em>
    </div>
</div>
<div class="row">
    <div class="column" align="left">
      <div class="row"><h2>Geocoding</h2></div>
    </div>
    <div class="column" align="center">
      <img class="medium" src="/media/VV_coh_4x19_geocoded.png">
      <em>Geocoded 6-days VV Coherence.</em>
    </div>
</div>


