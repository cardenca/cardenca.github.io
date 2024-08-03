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

# Publications
-----

<!-- {% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->

<!-- ### <span style="color:RoyalBlue"> <u> On the Parameters Domain of the Single-Diode Model </u> </span> <br> -->
## <u> On the Parameters Domain of the Single-Diode Model </u> <br>
*Carlos Cárdenas-Bravo, Denys Dutykh, and Sylvain Lespinats* <br>
*Published in Solar Energy, Elsevier, Jun. 2024.* <br> 
<a href="https://www.sciencedirect.com/science/article/pii/S0038092X24004134"> Read the full article here</a> <br> 

Preprints links: <a href="https://arxiv.org/abs/2407.07108#"> ArXiv </a>, <a href="https://hal.science/hal-04622649"> HAL open science </a>, <a href="https://www.authorea.com/users/797418/articles/1139566-on-the-parameters-domain-of-the-single-diode-model"> Authorea </a>.

<span font-size: smaller> **Abstract**: The current–voltage (I–V) curves of solar photovoltaic (PV) systems have been widely used as a tool to determine their electrical operation. Usually, I–V curves are described employing three cardinal points: the short-circuit point $$(0,\,I_\mathrm{sc})$$, the open-circuit point $$(V_\mathrm{oc},\,0)$$, and the maximum power point $$(V_\mathrm{mp},\,I_\mathrm{mp})$$. In this context, to study the I–V curves, the single-diode model (SDM) is often used. In this manuscript, we present a practical approach for determining the parameters domain of the SDM given a set of cardinal points. An in-depth mathematical analysis showed that the SDM must satisfy the following inequalities $$\frac{V_\mathrm{oc}}{2} < V_\mathrm{mp} < V_\mathrm{oc}$$ and $$\frac{I_\mathrm{sc}}{2} < I_\mathrm{mp} < I_\mathrm{sc}$$. Then, it is possible to implicitly represent the SDM by a single parameter and, consequently, to determine its domain. For this purpose, a fast open-source computational algorithm for the single parameter domain of the SDM is presented. The algorithm has been computer-tested using $$40\,000$$ synthetically generated maximum power points which are processed in about one minute of the CPU time on a standard laptop computer. Moreover, as practical applications, the databases from the California Energy Commission and the NREL are analyzed using the presented algorithm. </span>

## <u> Optimal design and experimental test of a solar simulator for solar photovoltaic modules </u> <br>
*Rodrigo Cortés-Severino, Carlos Cárdenas-Bravo, Rodrigo Barraza, Antonio Sánchez-Squella, Patricio Valdivia Lefort, and Federico Castillo-Burns* <br>
*Published in Energy & Engineering, Wiley, Oct. 2021.* <br> 
<a href="https://scijournals.onlinelibrary.wiley.com/doi/full/10.1002/ese3.985"> Read the full article here </a> 

<span font-size: smaller> **Abstract**: Solar simulators have been widely used to characterize the performance of solar photovoltaics cells, which typically have a size of 156 × 156 mm2. In order to amplify the testing area, a flexible optimal design method for solar simulators is presented in this study. In this work, 20 quartz tungsten halogen lamps are used with a light filter composed of a mixture of distilled water and cyan ink. The methodology includes the measurements of the irradiance nonuniformities, spectral profile, and explores the effects of light filters on the primary light source used. During this stage, the power source of the lights should be selected, where direct current is usually assumed. As soon as the primary light source is characterized by its corresponding model, a layout is defined by optimizing the nonuniformity of the irradiance. The constructed solar simulator presents a spectral match of 1.69%, a spatial nonuniformity of irradiance of 1.66%, and a temporal instability of irradiance lower than 0.1%. In addition, the current-voltage curves are compared under indoor and outdoor test showing a root-mean-squared error lower than 3%. A class CAA solar simulator is achieved according to the International Electrotechnical Commission and American Society for Testing and Materials standards over an area of 270 × 270 mm2, suitable for testing small size solar photovoltaic modules. </span>

## <u> Estimation of Single-Diode Photovoltaic Model Using the Differential Evolution Algorithm with Adaptive Boundaries </u> <br>
*Carlos Cárdenas-Bravo, Rodrigo Barraza, Antonio Sánchez-Squella, Patricio Valdivia-Lefort, and Federico Castillo-Burns* <br>
*Published in Energies, MDPI, June 2021.* <br> 
<a href="https://www.mdpi.com/1996-1073/14/13/3925"> Read the full article here</a> 

<p><small> **Abstract**: This study proposes a calculation methodology that determines the optimal boundary parameters of the single-diode photovoltaic model. It allows the calculation of the single-diode photovoltaic model when no reference parameter boundaries are available. The differential evolution algorithm, integrated with a step-by-step boundary definition module, is used to calculate the optimal parameters of the single-diode photovoltaic model, improving the performance of the classic algorithm compared with other studies. The solution is validated by comparing the results with well-established algorithms described in the state-of-the-art, and by estimating the five important points (cardinal points) of an IV curve, namely short-circuit, maximum power, and open circuit points, using a database composed of 100 solar photovoltaic modules. The results show that an optimal set of parameter boundaries enables the differential evolution algorithm to minimize the error of the estimated cardinal points. Moreover, the proposed calculus methodology is capable of producing high-performance response photovoltaic models for different technologies and rated powers. <p></small>




## Conferences
-----


## Patents
-----






