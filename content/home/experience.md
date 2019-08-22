+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "Software Engineer, Machine Learning"
  company = "o9 Solutions"
  company_url = "https://www.o9solutions.com/"
  location = "Dallas, TX"
  date_start = "2019-08-19"
  date_end = ""
 
[[experience]]
  title = "Graduate Research Assistant"
  company = "University at Buffalo, SUNY"
  company_url = ""
  location = "Buffalo, NY"
  date_start = "2018-09-01"
  date_end = "2019-05-01"
  description = """Worked on cursor detection and tracking in Adobe Photoshop videos, in collaboration with Dr. Hailin Jin (Adobe Research) under the guidance of Dr. Junsong Yuan (University at Buffalo).

Implemented a fully unsupervised method that incorporated adaptive video-based cursor discovery; multi-scale template matching; and optimal path search to locate the highest scoring cursor trajectory in the entire video. 

Other methods that were tried, included Optical Flow, Deep Visual Embeddings and Transfer Learning. Our method is able to discover previously unseen mouse cursors in videos, despite fast movement and instant appearance changes in a fully unsupervised manner. It outperforms Online Tracking (TLD, CSRT, MIL), and Deep Learning based object detection methods (Faster-RCNN) which require large training datasets.
"""

+++
