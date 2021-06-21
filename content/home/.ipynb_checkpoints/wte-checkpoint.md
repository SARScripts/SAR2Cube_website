+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://wowchemy.com/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank" # See https://wowchemy.com/docs/page-builder/
headless = true # This file represents a page section.
active = false # Activate this widget? true/false
weight = 40 # Order that this section will appear.

title = "World Terrestrial Ecosystems"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

[design.background]
  # Apply a background color, gradient, or image.
  #  Uncomment (by removing `#`) an option to apply it.
  #  Choose a light or dark text color by setting `text_color_light`.
  #  Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
 
  # Background gradient.
  # gradient_start = "DarkGreen"
  # gradient_end = "ForestGreen"
 
  # Background image.
  # image = "image.jpg" # Name of image in `static/media/`.
  # image_darken = 0.6 # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  # image_size = "cover" # Options are `cover` (default), `contain`, or `actual` size.
  # image_position = "center" # Options include `left`, `center` (default), or `right`.
  # image_parallax = true # Use a fun parallax-like fixed background effect? true/false
 
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

The World Terrestrial Ecoystems after [Sayre et al. (2020)](https://www.sciencedirect.com/science/article/pii/S2351989419307231?via%3Dihub) were developed using the [United Nations Food and Agriculture Organization](http://www.fao.org/home/en/) (FAO) and [Intergovernmental Panel on Climate Change](https://www.ipcc.ch/) (IPCC) criteria for ecological zones and climate regions. The map is based on a spatial integration of climate zones, landforms and land cover:

<div>
  <img style="float: right; margin: 50px;" src="/media/WTE_components.png", width=50%/>
  <p style="float:left;"/>  
</div>

1. A *World Temperature Domains* layer was developed by analyzing thousands of meteorological stations over a 30-year record of observations.

2. A *World Moisture Domains* layer was similarly developed from precipitation observations.

3. A *World Landforms* layer was derived by aggregating the global implementation of the Hammond landforms after [Karagulle et al. (2017)](https://onlinelibrary.wiley.com/doi/abs/10.1111/tgis.12265).

4. A *World Vegetation and Land Cover* layer was derived from the ESA CCI global Land Cover [product 2015](http://maps.elie.ucl.ac.be/CCI/viewer/download/ESACCI-LC-Ph2-PUGv2_2.0.pdf).

<p style="clear:both">
The combination of the climate and terrain types with the land cover types produces 576 possible combinations of World Terrestrial Ecosystems, of which 431 were realized:
</p>

<p align="center" style="clear:both">
 <img src="/media/WTE431.png"/>
 <img src="/media/WTE431_Legend.png"//>
</p>

The full methodological details and input layer descriptions are found in [Sayre et al. (2020)](https://www.sciencedirect.com/science/article/pii/S2351989419307231?via%3Dihub).
