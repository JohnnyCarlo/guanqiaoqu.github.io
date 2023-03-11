---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<!---
The author with an asterisk (\*) next to the name is my supervisor.
-->

Published Papers 
==
1.  \[<font color = "red">GLOBECOM'2022</font>\] **Guanqiao Qu**, Chenguang He\*, Qian Chen, Weixiao Meng, "Resource allocation in vehicle-aided MIoT: How to enhance energy efficiency in packet uploading?," in *Proc. IEEE Global Communications Conference (GLOBECOM)*, Rio de Janeiro, Brazil, Dec. 2022, pp. 6247-6252.
2.  \[<font color = "red">ICC'2022</font>\] Chenguang He\*, **Guanqiao Qu**, Qian Chen, Weixiao Meng, "A clustering-routing method to preprocess data for massive Internet of things," in *Proc. IEEE International Conference on Communications (ICC)*, Seoul, Korea, May 2022, pp. 1635-1640.
3. \[<font color = "red">IWCMC'2021</font>\] Chenguang He\*, **Guanqiao Qu**, Shouming Wei, "A vehicular communication routing algorithm based on graph theory," in *Proc. 17th International Wireless Communications and Mobile Computing Conference (IWCMC)*, Harbin, China, Jun. 2021, pp. 2176-2181.
4. \[<font color = "red">WCMC</font>\] Chenguang He\*, **Guanqiao Qu**, Liang Ye, Shouming Wei, "A two-level communication routing algorithm based on vehicle attribute information for vehicular ad hoc network," *Wireless Communications and Mobile Computing*, vol. 2021, pp. 1–14, 2021.
5. \[<font color = "red">CSPS'2020</font>\] Chenguang He\*, **Guanqiao Qu**, Liang Ye, Shouming Wei, "A cluster routing algorithm based on vehicle social information for VANET," in *Proc. 9th International Conference on Communications, Signal Processing, and Systems (CSPS)* Jul. 2020, pp. 522-528.
<!---
    [*Click here to download.*](http://guanqiaoqu.com/files/CSPS'2020.pdf)
 -->
<!---
Under Review Papers
==
 -->
 
Patents
==
1. 何晨光\*，**曲冠桥**，陈倩，陈舒怡，孟维晓，杨宇. 一种面向海量节点的大规模自组网分簇组网方法. 公开号：CN115022938A. 受理专利. (Chenguang He\*, **Guanqiao Qu**, Qian Chen, Shuyi Chen, Weixiao Meng, Yu Yang. A clustering method for massive nodes in the large-scale ad hoc network. CN Patent CN115022938A. Sep. 6. 2022. Application Pending.)
2. 何晨光\*，**曲冠桥**，叶亮，马琳，王雨. 基于AODV协议的多节点自组网传输的模拟方法及模拟系统. 公开号：CN113746737B. 授权专利. (Chenguang He\*, **Guanqiao Qu**, Liang Ye, Lin Ma, Yu Wang. A simulation method and a simulation system for the multi-node ad hoc communication network based on the AODV routing protocol. CN Patent CN113746737B. Jun. 14. 2022. Application Granted.)
3. 叶亮，杨宇，马琳，张昱哲，何晨光\*，**曲冠桥**. 基于双极化天线的全双工自组网快速分簇方法. 公开号：CN114980174A. 受理专利. (Liang Ye, Yu Yang, Lin Ma, Yuzhe Zhang, Chenguang He\*, **Guanqiao Qu**. A fast clustering method for the full-duplex ad hoc network based on the dual-polarized antennas. CN Patent CN114980174A. Aug. 30. 2022. Application Pending.)
