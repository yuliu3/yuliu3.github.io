---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<ol>
  {% for publication in site.data.publications %}
    <li>
      {{ publication.authors }} ({{ publication.year }}). 
      "<em>{{ publication.title }}</em>." 
      {{ publication.publication }} 
      {% if publication.volume %}
        {{ publication.volume }}({{ publication.issue }}), 
      {% endif %}
      {% if publication.pages %}
        {{ publication.pages }}. 
      {% endif %}
      {% if publication.doi %}
        DOI: {{ publication.doi }}
      {% endif %}
    </li>
  {% endfor %}
</ol>

<!--
[1] Network Topology Design for Distributed Quantum Computing
<br> Yingling Mao, **Yu Liu**, Xiaojun Shang, and Yuanyuan Yang  <br> 
in Proceedings of IEEE 44th International Conference on Distributed Computing Systems (**IEEE ICDCS**), Jersey City, New Jersey, USA.

[2] Joint Virtual Network Function Placement and Flow Routing in Edge-Cloud Continuum
<br> Yingling Mao, Xiaojun Shang, **Yu Liu**, and Yuanyuan Yang  <br> 
in IEEE Transactions on Computers (**IEEE TC**), vol. 73, no. 3, pp. 872-886, March 2024, doi: 10.1109/TC.2023.3347671.

[3] Joint Task Offloading and Resource Allocation in Heterogeneous Edge Environments
<br> **Yu Liu**, Yingling Mao, Zhenhua Liu, and Yuanyuan Yang  <br> 
in IEEE Transactions on Mobile Computing (**IEEE TMC**), vol. 23, no. 6, pp. 7318-7334, June 2024, doi: 10.1109/TMC.2023.3335198.

[4] Deep Learning-Assisted Online Task Offloading for Latency Minimization in Heterogeneous Mobile Edge
<br> **Yu Liu**, Yingling Mao, Zhenhua Liu, and Yuanyuan Yang<br>
in IEEE Transactions on Mobile Computing (**IEEE TMC**), vol. 23, no. 5, pp. 4062-4075, May 2024, doi: 10.1109/TMC.2023.3285882.

[5] Availability Aware Online Virtual Network Function Backup in Edge Environments
<br>**Yu Liu**, Xiaojun Shang, Yingling Mao, Zhenhua Liu, and Yuanyuan Yang<br>
in IEEE Transactions on Mobile Computing (**IEEE TMC**), vol. 23, no. 5, pp. 3909-3922, May 2024, doi: 10.1109/TMC.2023.3282156.

[6] Probability-aware Qubit-to-Processor Mapping in Distributed Quantum Computing
<br> Yingling Mao, **Yu Liu**, and Yuanyuan Yang <br>
in Proceedings of ACM SIGCOMM 1st Workshop on Quantum Networks and Distributed Quantum Computing (**ACM QuNet**), New York, NY, USA, 2023, pp. 51–56, doi: 10.1145/3610251.3610554.

[7] Energy-Aware Online Task Offloading and Resource Allocation for Mobile Edge Computing
<br> **Yu Liu**, Yingling Mao, Xiaojun Shang, Zhenhua Liu, and Yuanyuan Yang <br>
in Proceedings of IEEE 43rd International Conference on Distributed Computing Systems (**IEEE ICDCS**), Hong Kong, 2023, pp. 339-349, doi: 10.1109/ICDCS57875.2023.00073.

[8] Joint Task Offloading and Resource Allocation in Heterogeneous Edge Environments
<br> **Yu Liu**, Yingling Mao, Zhenhua Liu, and Yuanyuan Yang <br> 
in Proceedings of IEEE Conference on Computer Communications (**IEEE INFOCOM**), New York City, NY, USA, 2023, pp. 1-10, doi: 10.1109/INFOCOM53939.2023.10229015.

[9] Qubit Allocation for Distributed Quantum Computing
<br> Yingling Mao, **Yu Liu**, and Yuanyuan Yang <br> 
in Proceedings of IEEE Conference on Computer Communications (**IEEE INFOCOM**), New York City, NY, USA, 2023, pp. 1-10, doi: 10.1109/INFOCOM53939.2023.10228915.

[10] Online Container Scheduling for Data-intensive Applications in Serverless Edge Computing
<br> Xiaojun Shang, Yingling Mao, **Yu Liu**, Yaodong Huang, Zhenhua Liu, and Yuanyuan Yang  <br> 
in Proceedings of IEEE Conference on Computer Communications (**IEEE INFOCOM**), New York City, NY, USA, 2023, pp. 1-10, doi: 10.1109/INFOCOM53939.2023.10229034.

[11] Online Resource Provisioning for Wireless Data Collection
<br>**Yu Liu**, Joshua Comden, Zhenhua Liu, and Yuanyuan Yang<br>
in ACM Transactions on Sensor Networks (**ACM TOSN**), vol. 18, no. 1, pp. 1-27, Feb. 2022, doi:10.1145/3470648.

[12] Distributed Cooperative Caching in Unreliable Edge Environments
<br> **Yu Liu**, Yingling Mao, Xiaojun Shang, Zhenhua Liu, and Yuanyuan Yang  <br> 
in Proceedings of IEEE Conference on Computer Communications (**IEEE INFOCOM**), London, United Kingdom, 2022, pp. 1049-1058, doi: 10.1109/INFOCOM48880.2022.9796799.

[13] Joint SFC Deployment and Resource Management in Heterogeneous Edge for Latency Minimization
<br>**Yu Liu**, Xiaojun Shang, and Yuanyuan Yang<br>
in IEEE Transactions on Parallel and Distributed Systems (**IEEE TPDS**), vol. 32, no. 8, pp. 2131-2143, 1 Aug. 2021, doi: 10.1109/TPDS.2021.3062341.

[14] Online Cloud Resource Provisioning Under Cost Budget for QoS Maximization
<br> **Yu Liu**, Niangjun Chen, Zhenhua Liu, and Yuanyuan Yang <br>
in Proceedings of IEEE/ACM 29th International Symposium on Quality of Service (**IEEE/ACM IWQOS**), Tokyo, Japan, 2021, pp. 1-6, doi: 10.1109/IWQOS52092.2021.9521347.

[15] Greening reliability of virtual network functions via online optimization
<br> Xioajun Shang, **Yu Liu**, Yingling Mao, Zhenhua Liu, and Yuanyuan Yang  <br>
in Proceedings of IEEE/ACM 28th International Symposium on Quality of Service (**IEEE/ACM IWQoS**), Hang Zhou, China, 2020, pp. 1-10, doi: 10.1109/IWQoS49365.2020.9212998.

[16] Non-stationary stochastic network optimization with imperfect estimations
<br> **Yu Liu**, Zhenhua Liu, and Yuanyuan Yang  <br>
in Proceedings of IEEE 39th International Conference on Distributed Computing Systems (**IEEE ICDCS**), Dallas, TX, USA, 2019, pp. 431-441, doi: 10.1109/ICDCS.2019.00050.

[17] Multi-Rack Regenerating Codes for Hierarchical Distributed Storage Systems
<br> Shan Qu, **Yu Liu**, Jinbei Zhang, Haiwen Cao and Xinbing Wang,  <br>
in Proceedings of IEEE International Conference on Communications (**IEEE ICC**), Kansas City, MO, USA, 2018, pp. 1-6, doi: 10.1109/ICC.2018.8422112.
-->
