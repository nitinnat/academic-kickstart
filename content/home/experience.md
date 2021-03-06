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

[[experience]]
  title = "Student Research Assistant"
  company = "University at Buffalo, SUNY"
  company_url = ""
  location = "Buffalo, NY"
  date_start = "2017-09-01"
  date_end = "2018-11-01"
  description = """  
  1. GADGET - A gossip-based sub-gradient solver, that aims to determine a solution for the primal SVM in a distributed setting. I worked on several improvements for an existing C++/Java/JNI code-base, ran baseline experiments, wrote scripts to aggregate results, and performed a literature review. Ported code to pure Java using the Weka library.  
  Tech stack - Java, C++, Java Native Interface (JNI), Python, Peersim (A distributed simulator), Weka 
  
  2. Named Entity Recognition on tweets.  
  Tech stack: Java, StanfordNLP.  
  
  3. Vanilla, Lasso and Ridge Logistic Regression for the problem of detecting inter-group prejudice in tweets.  
  Tech stack: R
"""


[[experience]]
  title = "Applied Machine Learning Intern"
  company = "Clarifai"
  company_url = "https://www.clarifai.com/"
  location = "New York, NY"
  date_start = "2018-05-29"
  date_end = "2018-08-24"
  description = """  
  1. Object tracking and detection - Developed a hybrid single-object tracker based on existing research that interleaved detection at regular intervals to combat the problem of tracker drift.  
  
  2. Depth sensor noise characterization - Characterized and visualized the temporal noise distributions of depth and confidence maps provided by an industry-grade depth camera. Wrote several helper scripts to obtain and store images from the camera into the appropriate format, keeping in mind the pitfalls of image compression when it comes to storing large, high quality images.  
  
  3. Visualization - Extended and modified an existing video/image visualization framework to incorporate several functionalities.  
  Tech Stack: Python, Tensorflow, Git, Matplotlib, ZED Depth Camera
"""

[[experience]]
  title = "Software Engineer"
  company = "Fidelity Investments"
  company_url = "https://india.fidelity.com"
  location = "Bengaluru, India"
  date_start = "2016-08-01"
  date_end = "2017-07-01"
  description = """  
  1. Conversational Chat Interface:  
  
    * Agile development of an enterprise-wide chatbot based on ontology, natural language processing and machine learning approaches, to offload internal customer service desk interactions.  
    * Proposed and developed hybrid APIs for query expansion and response retrieval using semantic word embeddings, synonym augmentation, query ranking and topic classification.
    * Experimented with Deep Learning architectures using sequence to sequence learning.  
    * Enabled containerization of several code components using Docker.  
  2. Sentiment Analysis:  
  
    * Created a sentiment and skill mining tool to retrieve employee-based insights, aiding senior management in the assessment of employee training opportunities.  
    * Analyzed and processed complex unsupervised relational text data.  
    * Applied Support Vector Machines, Naive Bayes and LSTM classifiers for a cross-validation accuracy of over 93 percent.
"""

[[experience]]
  title = "Executive Graduate Trainee"
  company = "Fidelity Investments"
  company_url = "https://india.fidelity.com"
  location = "Bengaluru, India"
  date_start = "2015-06-11"
  date_end = "2016-08-01"
  description = """  
  1. Managed reporting and analytics solutions for a team of 120 associates in India, United States and China.  
  2. Analyzed and consolidated KPIs from data stored in several relational databases using Python and SQL.
  3. Created interactive operational and performance dashboards using Tableau.
  4. Interacted regularly with senior management to propose and modify crucial KPIs.
"""

+++
