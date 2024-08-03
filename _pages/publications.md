---
# layout: archive
title: "Scientific production"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

Publications
-----

<!-- {% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->

<!-- ### <span style="color:RoyalBlue"> <u> On the Parameters Domain of the Single-Diode Model </u> </span> <br> -->
### <u> On the Parameters Domain of the Single-Diode Model </u> <br>
*Carlos Cárdenas-Bravo, Denys Dutykh, and Sylvain Lespinats* <br>
*Published in Solar Energy, Elsevier, Jun. 2024.* <br> 
<a href="https://www.sciencedirect.com/science/article/pii/S0038092X24004134"> Read the article here</a> <br> 

Preprints links: <a href="https://arxiv.org/abs/2407.07108#"> ArXiv </a>, <a href="https://www.sciencedirect.com/science/article/pii/S0038092X24004134"> HAL </a>, <a href="https://www.sciencedirect.com/science/article/pii/S0038092X24004134"> HAL </a>.


<span font-size: smaller> **Abstract**: The current–voltage (I–V) curves of solar photovoltaic (PV) systems have been widely used as a tool to determine their electrical operation. Usually, I–V curves are described employing three cardinal points: the short-circuit point \\( 0,\,I_\mathrm{sc}\\), the open-circuit point \\( V_\mathrm{oc},\,0 \\), and the maximum power point \\( V_\mathrm{mp},\,I_\mathrm{mp}\\). In this context, to study the I–V curves, the single-diode model (SDM) is often used. In this manuscript, we present a practical approach for determining the parameters domain of the SDM given a set of cardinal points. An in-depth mathematical analysis showed that the SDM must satisfy the following inequalities \\( \frac{V_\mathrm{oc}}{2} < V_\mathrm{mp} < V_\mathrm{oc}\\) and \\( \frac{I_\mathrm{sc}}{2} < I_\mathrm{mp} < I_\mathrm{sc}\\). Then, it is possible to implicitly represent the SDM by a single parameter and, consequently, to determine its domain. For this purpose, a fast open-source computational algorithm for the single parameter domain of the SDM is presented. The algorithm has been computer-tested using $$40\,000$$ synthetically generated maximum power points which are processed in about one minute of the CPU time on a standard laptop computer. Moreover, as practical applications, the databases from the California Energy Commission and the NREL are analyzed using the presented algorithm. </span>


### <u> Estimation of Single-Diode Photovoltaic Model Using the Differential Evolution Algorithm with Adaptive Boundaries </u> <br>
*Carlos Cárdenas-Bravo, Rodrigo Barraza, Antonio Sánchez-Squella, Patricio Valdivia-Lefort, and Federico Castillo-Burns* <br>
*Published in Energies, MDPI, June 2021.* <br> 
<a href="https://www.mdpi.com/1996-1073/14/13/3925"> Read the article here</a> 

<span font-size: smaller> **Abstract**: This study proposes a calculation methodology that determines the optimal boundary parameters of the single-diode photovoltaic model. It allows the calculation of the single-diode photovoltaic model when no reference parameter boundaries are available. The differential evolution algorithm, integrated with a step-by-step boundary definition module, is used to calculate the optimal parameters of the single-diode photovoltaic model, improving the performance of the classic algorithm compared with other studies. The solution is validated by comparing the results with well-established algorithms described in the state-of-the-art, and by estimating the five important points (cardinal points) of an IV curve, namely short-circuit, maximum power, and open circuit points, using a database composed of 100 solar photovoltaic modules. The results show that an optimal set of parameter boundaries enables the differential evolution algorithm to minimize the error of the estimated cardinal points. Moreover, the proposed calculus methodology is capable of producing high-performance response photovoltaic models for different technologies and rated powers. </span>




Conferences
-----


Patents
-----






