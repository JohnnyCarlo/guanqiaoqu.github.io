---
layout: archive
title: "Research Projects"
permalink: /projectss/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Research Projects
==
1. **A Software Development (\*\*\*\*\*\*\*\*\*\*\*\*)**
* Basic Strengthening Key Projects
* Sep 2021 – Present
* Supervisor: Chenguang He, Lin Ma, Liang Ye, Weixiao Meng
* Details
  * Designed the communication scheme.
  * Proposed and simulated four communication algorithms according to the requirements of the nodes.
  * Tools: Linux, C++, MATLAB

2. **China-Chile ICT "The Belt and Road" Joint Laboratory Construction and Joint Research (SQ2020YFE020708)**
* National Science and Technology Project
* Sep 2021 – Present
* Supervisor: Chenguang He, Shuyi Chen, Weixiao Meng
* Details
  * Designed the communication model for Massive IoT devices in areas without the cellular network to access the cellular network with vehicular ad hoc networks.
  * Proposed the communication scheme to minimize total network energy consumption and maximize communication reliability by optimizing communication strategy and relay selection.
  * Exploited the communication scheme to maximize the energy efficiency of uploading packets from Massive IoT devices to the vehicles by jointly optimizing the network resources allocation and connection strategy.
  * Developed the packet forwarding and offloading algorithm by considering the data QoS requirements, vehicles’ positions on the real roads, and network offload to decide packet forwarding and offloading strategies. 
  * Tools: MATLAB, Simulation of Urban MObility (SUMO)

3. **Research on \*\*\*\*\*\*\*\*\* and Transmission Optimization Technology (\*\*\*\*\*\*\*\*\*\*\*\*)**
* Enterprise Cooperation Project
* Sep 2020 – Oct 2020
* Supervisor: Chenguang He, Lin Ma, Liang Ye, Shuai Han, Weixiao Meng
* Details
  * Simulated parallel communications of nodes under AOMDV routing protocol and measured network performance.
  * Tools: Network Simulator version 2 (NS-2)

4. **Research on Communication Technology of Indoor-and-Outdoor Unmanned Clustering WANET (F2100115)**
* Enterprise Cooperation Project
* Sep 2019 – Mar 2021
* Supervisor: Chenguang He, Lin Ma, Liang Ye, Shuai Han, Weixiao Meng
* Details
  * Made the network interface card into ad hoc networks by using AODV routing protocol.
  * Developed a program based on UDP protocol and socket interface to extend the simple case to the general case.  
  * Simulated the hop counts and delays when multiple virtual nodes communicate.
  * Tools: Linux, C++

5. **Research on Cluster Routing Algorithm Based on Vehicle Attribute Information for Vehicular Ad Hoc Network**
* Bachelor thesis in HIT
* Sep 2019 – Jun 2020
* Supervisor: Chenguang He
* Details
  * Investigated the existing routing and clustering algorithms.
  * Proposed a clustering-routing algorithm based on vehicles’ attribute information to establish efficient and stable routes with low-latency.
  * Tools: NS-2, SUMO, MATLAB
