---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<style type="text/css">
    h1 { counter-reset: h2counter; }
    h2 { counter-reset: h3counter; }
    h3 { counter-reset: h4counter; }
    h4 { counter-reset: h5counter; }
    h5 { counter-reset: h6counter; }
    h6 { }
    h2:before {
      counter-increment: h2counter;
      content: counter(h2counter) ".\0000a0\0000a0";
    }
    h3:before {
      counter-increment: h3counter;
      content: counter(h2counter) "."
                counter(h3counter) ".\0000a0\0000a0";
    }
    h4:before {
      counter-increment: h4counter;
      content: counter(h2counter) "."
                counter(h3counter) "."
                counter(h4counter) ".\0000a0\0000a0";
    }
    h5:before {
      counter-increment: h5counter;
      content: counter(h2counter) "."
                counter(h3counter) "."
                counter(h4counter) "."
                counter(h5counter) ".\0000a0\0000a0";
    }
    h6:before {
      counter-increment: h6counter;
      content: counter(h2counter) "."
                counter(h3counter) "."
                counter(h4counter) "."
                counter(h5counter) "."
                counter(h6counter) ".\0000a0\0000a0";
    }
</style>
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

The author with an asterisk (\*) next to the author's name is my tutor Associate Professor Chenguang He.

# Accepted Papers 
1. Chenguang He\*, **Guanqiao Qu**, Qian Chen, Weixiao Meng, "A clustering-routing method to preprocess data for massive Internet of things," *2022 IEEE International Conference on Communications (ICC)*. 2022.  

Published Papers 
===
**1.** Chenguang He\*, **Guanqiao Qu**, Liang Ye, Shouming Wei, "A cluster routing algorithm based on vehicle social information for VANET," in *Proc. 9th International Conference on Communications, Signal Processing, and Systems (CSPS)* Jul. 2020, pp. 522-528.

[*Click here to download.*](http://guanqiaoqu.com/files/CSPS'2020.pdf)

**2.** Chenguang He\*, **Guanqiao Qu**, Liang Ye, Shouming Wei, "A two-level communication routing algorithm based on vehicle attribute information for vehicular Ad Hoc
network," *Wireless Communications and Mobile Computing*, vol. 2021, pp. 1–14, 2021.

[*Click here to download.*](http://guanqiaoqu.com/files/WCMC.pdf)

**3.** Chenguang He\*, **Guanqiao Qu**, Shouming Wei, "A vehicular communication routing algorithm based on graph theory," in *Proc. 17th International Wireless Communications and Mobile Computing Conference (IWCMC)*, Harbin, China, Jun. 2021, pp. 2176-2181.
<!---
Proc. 17th Int. Wireless Commun. Mobile Comput. Conf. (IWCMC)
-->

[*Click here to download.*](http://guanqiaoqu.com/files/IWCMC'2021.pdf)


Accepted Patents
===
**1.** 何晨光\*，**曲冠桥**，叶亮，马琳，王雨. 基于AODV协议的多节点自组网传输的模拟方法及模拟系统. 申请号：202111033022.4.

**1.** Chenguang He\*, **Guanqiao Qu**, Liang Ye, Lin Ma, Yu Wang. 2021. Simulation method and system of multi-node Ad Hoc network transmission based on AODV. C.N. Patent Application 202111033022.4, filed September 2021 Patent Pending.
