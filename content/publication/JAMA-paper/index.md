---
abstract: The American Psychiatric Association (APA) Annual Meeting was one of many events to be made virtual during the COVID-19 global shutdown. Reduced air travel significantly improved global air and water quality during this time.^[1,2] We sought to estimate the carbon footprint of the past two APA meetings as a proxy for the carbon emissions avoided by holding the 2020 APA Annual Meeting virtually. Using this data we assess how the location of APA meetings impacts this carbon footprint and develop conservative estimates of CO2*e* emissions from each attendee's travel in 2018 and 2019 to create counterfactual scenarios to quantify theoretical carbon footprints had the meetings been held in the locations of the past 40 APA meetings instead. Using the attendees’ cities of origin and a geo-location application programming interface paired with a global airport database, we identified likely transport modes and routes each attendee would use to travel to and from the meetings then applied an emissions function to the ground and air legs. The carbon footprint of the New York City 2018 and San Francisco 2019 meetings were 19,819 (1.19 per Capita) metric tons CO2*e* and 21,456 (1.61 per Capita) metric tons CO2*e*, respectively. This means the carbon footprint of each conference was equivalent to burning about 500 acres of dense forest or 22 million pounds of coal. Counterfactual scenarios at previous locations in the Western US and Hawai'i increased the total carbon footprint by 60% - 164% compared to meetings held in the Northeastern US. These findings were further confirmed by an unconstrained geometric minimization algorithm that sampled 100,000 random coordinates across the globe. This study shows that the CO2*e* emissions of the APA Annual Meetings are significant and that optimizing conference location or intermittently making the conference virtual can dramatically lower this carbon footprint.
authors:
- Joshua R. Wortzel
- Alec Stashevsky
- Jeremy D. Wortzel
- Beth Mark
- Janet Lewis
- Elizabeth Haase
date: "2021-01-28"
doi: "10.1001/jamanetworkopen.2020.35641"
featured: true
image:
  caption: "Geodesic Distances of NYC 2018 Meeting Attendees"
  focal_point: ""
  preview_only: false
projects: []
publication: '*JAMA Network Open, 4*(1)'
publication_short: ""
publication_types:
- "2"
publishDate: "2021-01-28"
slides: 
summary: In the wake of the Coronavirus pandemic the APA canceled their 2020 Annual Meeting. We sought to estimate the avoided carbon emissions from holding the conference virtually and explore the impact of strategic planning.
tags:
title: Estimation of the Carbon Footprint Associated With Attendees of the American Psychiatric Association Annual Meeting
url_pdf:
links:
 - name: "Code Supplement"
   url: https://github.com/Alec-Stashevsky/GAP-climate-research
   icon_pack: fab
   icon: github
---

The code for this analysis is available at my [GitHub.](https://github.com/Alec-Stashevsky/GAP-climate-research)

I would like to thank my coauthors, especially Josh Wortzel and Elizabeth Haase for this opportunity for which I am so grateful. 

I would also like to thank [GoClimate](https://www.goclimate.com/) for granting us access to their [Flight Emisions API.](https://api.goclimate.com/docs)