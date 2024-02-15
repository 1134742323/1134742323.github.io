---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

* * = Corresponding author

5. **Liu, Z.**, & Wong, L. N. Y.* (2024). A new thermomechanical coupled FDEM model for geomaterials considering continuum-discontinuum transitions. *Journal of Rock Mechanics and Geotechnical Engineering*. [Download paper here](https://doi.org/10.1016/j.jrmge.2023.12.005)
4. Wong, L. N. Y., **Liu, Z.***, Tse, K. K. C., Cheung, S. H., & Yu, L. (2023). A Computational Algorithm for Calculating Fracture Index of Core Runs. *Rock Mechanics and Rock Engineering*, 56, 6905–6918. [Download paper here](https://doi.org/10.1007/s00603-023-03422-z)
3. **Liu, Z.**, Zhang, Z.*, & Ghassemi, A. (2021). Bedding plane-embedded augmented virtual internal bonds for fracture propagation simulation in shale. *Theoretical and Applied Mechanics Letters*, 11(3), 100253. [Download paper here](https://doi.org/10.1016/j.taml.2021.100253)
2. **Liu, Z.**, Jiang, N.*, Zhou, C., Ji, L., & Luo, X. (2021). Damage Effect of Terrorist Attack Explosion-induced Shock Wave in a Double-deck Island Platform Metro Station. *Periodica Polytechnica Civil Engineering*, 65(1), 215-228. [Download paper here](https://doi.org/10.3311/PPci.16929)
1. **Liu, Z.**, Jiang, N.*, Sun, J., Xia, Y., & Lyu, G. (2020). Influence of tunnel blasting construction on adjacent highway tunnel: A case study in Wuhan, China. *International Journal of Protective Structures*, 11(3), 283-303. [Download paper here](https://doi.org/10.1177/2041419619888936)


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


