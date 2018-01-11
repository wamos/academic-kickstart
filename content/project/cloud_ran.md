+++
# Date this page was created.
date = "2016-06-11"

# Project title.
title = "Modeling Cloud Radio Access Networks Performance on Container Cloud"

# Project summary to display on homepage.
summary = "Software-based LTE on Docker and Openstack"

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "cloud.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["cloud", "mobile"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = true

# Optional featured image (relative to `static/img/` folder).
#[header]
#image = "cloud.png"
#caption = "CCO:Common Creative"

+++
As the huge growth of mobile traffic amount, conventional Radio Access Networks (RANs) suffer from high capital and operating expenditures, especially when new cellular standards are deployed. Software, and cloud RANs have been proposed, but the stringent latency requirements e.g., 1 ms transmission time interval, dictated by cellular networks is difficult to satisfy. We first present a real software RAN testbed based on an opensource LTE implementation. We also investigate the issue of quality assurance when deploying such software RANs in cloud. In particular, running software RANs in cloud leads to high latency, which may violate the latency requirements. We empirically study the problem of minimizing computational and networking latencies in lightweight container cloud. Our experiment results show the feasibility of running software RANs in real-time container cloud. More specifically, a feasible solution to host software RANs in cloud is to adopt lightweight containers with real-time kernels and fast packet processing networking.


