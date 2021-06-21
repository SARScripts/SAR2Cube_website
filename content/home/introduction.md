+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://wowchemy.com/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://wowchemy.com/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 20  # Order that this section will appear.

title = "Project background"
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

One of the biggest entry level hurdles for integrating SAR data into modern earth observation analysis chains, is still the complexity of the data itself. Opposed to optical or multi-spectral data, which relates much more directly to the way human vision works and is hence more natural to interpret, SAR registers signals that are not natural to human senses, both due to the typically sight looking geometry and to the wavelengths of the electromagnetic spectrum in which SAR typically operates. Operating in this very different spectrum, however, gives the SAR signals unique characteristics, which can be extremely beneficial in many observation scenarios. One of the most obvious and often quoted is the ability to see through clouds and hence SAR is providing a more reliable data source in areas that are frequently cloud covered. Another important domain of SAR are the interferometric observations, which allow for detection of terrain movements or the change of signal strength over time and finally polarimetry, which allows for assumptions on the scatter mechanisms in the physical path of the signal.

SAR2CUBE as a project foresees the development of a processing chain and prototype implementation for organizing Sentinel-1 SLC data in efficient data cubes, both from the point of view of the data provider and from the point of view of the consumer of the data, in order to foster the uptake of SAR data into everyday processing chains. This comprises three main layers, pre-processing, data cube setup and post processing on the fly. A number of different implementation scenarios are planned to be benchmarked in a performance test suite, including necessary space requirements for hosting the data and speed of access from the user perspective. Finally, three use cases have been defined to test the suitability of the developed SAR data cubes for analysis chains, including analysis of terrain motion with PSI techniques, land cover classification based on interferometric coherence and change detection based on back scatter time series.

