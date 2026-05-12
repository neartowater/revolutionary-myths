---
title: Revolutionary Myths
layout: base
date: 2025-10-21
header-image: "/assets/images/history_of_mexico.jpg"
header-title: The Artwork of Revolutionary Myths of Latin America During the 20th Century 
header-subtitle: Biographies
header-position: 35% center
---

# Revolutionary Myths

Since the onset of European colonization of the western hemisphere began in 1492, there have been a number of resistance movements that have propagated throughout Latin America protesting inhumane treatment, tyrannical rule, and unequal systems of hierarchy. There is no typology or official standard for qualifying a resistance movement as a revolution, however, movements that remove leaders from power and replace them with formerly oppressed people is a characteristic of a revolution. Some revolutions, as is the case with Haiti, result in a complete inversion of the hierarchy. In Haiti's case, slaves became free overnight while the ruling elites were stripped of all their power and posesssions. While in Mexico, the revolution resulted in the overthrow of Porfirio Diaz but control of the goverment remained in the hands of the elites, rather than the people. Despite their outcomes, the consistent factor with revolutionary movements is the myths that fuel their beginnings. Revolutinary myths evoke strong imagery that appeals to the intuitive and emotional nature of its audience. These images are often abstract and irrational because they resonate with the hopes, apirations, and motivations of a country's citizenry, they need to convey a legacy and a future that words cannot describe.    

The interactive modules explore different Latin American countries and the art that conceptualized their revolution: Haiti, Mexico, Cuba, Chilé, Nicaragua, and Venezuela.  



{% assign all_pages = site.pages %}
{% assign cards = all_pages | where_exp: "p", "p.path contains 'essays/'" | where_exp: "p", "p.path != 'essays/index.md'" %}

{% include nav/card-grid.html cards=cards %}

