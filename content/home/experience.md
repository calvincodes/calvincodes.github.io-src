+++
# Experience widget.
widget = "experience"  # Do not modify this line!
active = true  # Activate this widget? true/false

title = "Experience"
subtitle = ""

# Order that this section will appear in.
weight = 2

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "January 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "Backend Software Engineering Intern"
  company = "Sumo Logic"
  company_url = "https://www.sumologic.com/"
  location = "Redwood City, USA"
  date_start = "2019-06-28"
  description = """
  Projects:
  
  * Working on letting an authorized user switch across organizations without having to re-login for each organization.
  """

[[experience]]
  title = "Senior Software Engineer"
  company = "Myntra Designs Pvt. Ltd."
  company_url = "https://www.myntra.com/"
  location = "Bengaluru, India"
  date_start = "2015-07-01"
  date_end = "2018-07-20"
  description = """
  Projects:
  
  * Decoupled order taking & order processing services using message-queueing via RabbitMQ. Achieved scalability of handling ∼150,000 requests/min in the Java based order taking service & processing ∼1,000,000 (1M) messages/min using RabbitMQ. Detailed analysis is available on my [tech blog](https://medium.com/calvin-codes/using-spring-rabbit-under-high-throughput-520ff76d3dd6).
  * Built an asynchronous micro-service in Play, capable of taking ∼10,000 requests/min on a single server with a response time of ∼100 ms. It is being used to identify optimal warehouse during order checkout.
  * Built a micro-service in Play, for customer order consolidation, saving ∼$700,000/day of supply chain cost.
  * Designed invoice generation module for customer orders, using Java and Apache Velocity. Also identified a bug in Velocity and published its workaround on my [tech blog](https://medium.com/calvin-codes/velocity-could-not-be-initialised-but-why-514f7708cc13).
  """

[[experience]]
  title = "Summer Research Assistant"
  company = "Hanyang University (ERICA)"
  company_url = "http://www.hanyang.ac.kr/web/eng/erica-campus1"
  location = "Ansan, S. Korea"
  date_start = "2014-05-01"
  date_end = "2014-07-10"
  description = """
  Project:
  
  * Developed a Korean script keyboard as an input method editor for android operating system. It provides auto-completion suggestions from a database of 30,000 (30K) Korean words.
  * Used File and SharedPreferences APIs to create an application extending InputMethodService.
  """
  
[[experience]]
  title = "Summer Research Assistant"
  company = "Indian Institute Of Technology Hyderabad"
  company_url = "https://www.iith.ac.in/"
  location = "Hyderabad, India"
  date_start = "2013-05-01"
  date_end = "2013-07-10"
  description = """
  Project:
  
  * Developed an on chip architecture for the detection and identification of fragmented QRS complex in ECG signals.
  * Developed parallel worker units to reduce the time complexity of the detection algorithm. Used Verilog for the implementation.
  """

+++
