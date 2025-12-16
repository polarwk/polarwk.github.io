---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{[author.googlescholar](https://scholar.google.com/citations?hl=zh-CN&user=lV0TgyMAAAAJ)}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

# Publication

* Kai Wang, Michael Wen Tong, Jun Pang, Jitao Wang, Weili Han. XRAD: Ransomware Address Detection Method based on Bitcoin Transaction Relationships. ACM Transactions on the Web (TWEB), 2024.
* Kai Wang, Yakun Cheng, Michael Wen Tong, Zhenghao Niu, Jun Pang, Weili Han. Exploring Unconfirmed Transactions for Effective Bitcoin Address Clustering. In Proceedings of the ACM Web Conference 2024 (WWW’24 CCF A), Singapore, May 13–17, 2024: 1880-1891. (Oral Presentation, Oral Rate: 189/2004=9.4\%) 
* Kai Wang, Jun Pang, Dingjie Chen, Yu Zhao, Dapeng Huang, Chen Chen, Weili Han. A Large-scale Empirical Analysis of Ransomware Activities in Bitcoin. ACM Transactions on the Web (TWEB CCF B), 2022, 16(2): 1-29.
* Weili Han, Dingjie Chen, Jun Pang, Kai Wang, Chen Chen, Dapeng Huang, Zhijie Fan. Temporal Networks based Industry Identification for Bitcoin Users. In Proceedings of The 16th International Conference on Wireless Algorithms, Systems, and Applications (WASA CCF C), Nanjing, China, June 25–27, 2021: 108-120.
* Dapeng Huang, Haorang Chen, Chen Chen, Kai Wang, Weili Han. A Traceability Method for Bitcoin Transactions Based on Gateway Network Traffic Analysis. In Proceedings of 2022 International Conference on Networking and Network Applications (NaNA), Urumqi, China, 2022: 176-183. (Best Paper Award).
* Dapeng Huang, Chen Chen, Haowei Luo, Kai Wang, Weili Han. A Bitcoin Transaction Analyzing and Tracking Mechanism in Specified Network Zone. Journal of Information Science & Engineering (JISE), 2024, 40(2): 375-396.
* Jitao Wang, Bo Zhang, Kai Wang, Yuzhou Wang, Weili Han. BFTDiagnosis: An Automated Security Testing Framework with Malicious Behavior Injection for BFT Protocols. Computer Networks (CN CCF B), 2024.