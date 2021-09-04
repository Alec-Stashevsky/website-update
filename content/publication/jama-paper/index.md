---
abstract: The American Psychiatric Association (APA) Annual Meeting was one of many events to be made virtual during the COVID-19 global shutdown. Reduced air travel significantly improved global air and water quality during this time [*See* [Venter et al. (2020)](https://doi.org/10.1073/pnas.2006853117) and [Yunus, Masago, and Hijioka (2020)](https://doi.org/10.1016/j.scitotenv.2020.139012)]. We sought to estimate the carbon footprint of the past two APA meetings as a proxy for the carbon emissions avoided by holding the 2020 Annual Meeting virtually. Using anonymized attendance data we assess how the location of APA meetings impacts this carbon footprint and develop conservative estimates of carbon dioxide equivalent (CO<sub>2</sub>*e*) emissions from each attendee's travel in 2018 and 2019. We create counterfactual scenarios to quantify carbon footprints had the meetings been held at locations of the past 40 APA meetings instead. We identify likely transport modes and routes each attendee would use to travel to and from the meetings then apply an emissions function to the ground and air legs. The carbon footprint of the New York City 2018 and San Francisco 2019 meetings are 19,819 (1.19 per Capita) metric tons CO<sub>2</sub>*e* and 21,456 (1.61 per Capita) metric tons CO<sub>2</sub>*e*, respectively. This means the carbon footprint of each conference was equivalent to burning about 500 acres of dense forest or 22 million pounds of coal. Counterfactual scenarios at previous locations in the Western US and Hawaii increased the total carbon footprint by 60% - 164% compared to meetings held in the Northeastern US. These findings were further confirmed by an unconstrained geometric minimization algorithm that sampled 100,000 random coordinates across the globe. This study shows that the CO<sub>2</sub>*e* emissions of the APA Annual Meetings are significant and that optimizing conference location or intermittently making the conference virtual can dramatically lower this carbon footprint.
authors:
- Joshua R. Wortzel
- Alec Stashevsky
- Jeremy D. Wortzel
- Beth Mark
- Janet Lewis
- Elizabeth Haase
date: "2021-01-28T00:00:00Z"
doi: "10.1001/jamanetworkopen.2020.35641"
featured: true
image:
  caption: "Geodesic Distances of NYC 2018 Meeting Attendees"
  focal_point:
  preview_only: true
publication: '*JAMA Network Open, 4*(1)'
publication_types:
- "2"
publishDate: "2021-01-28T00:00:00Z"
summary: In the wake of the Coronavirus pandemic the APA canceled their 2020 Annual Meeting. We sought to estimate the avoided carbon emissions from holding the conference virtually and explore the impact of strategic planning for future meetings.
tags:
title: Estimation of the Carbon Footprint Associated With Attendees of the American Psychiatric Association Annual Meeting
url_pdf: "/publication/jama-paper/wortzel_APA_carbon_footprint.pdf"
links:
 - name: "Code Supplement"
   url: https://github.com/Alec-Stashevsky/GAP-climate-research
   icon_pack: fab
   icon: github
slides: jama-paper
---

[Read the full article here!](https://doi.org/10.1001/jamanetworkopen.2020.35641 "JAMA Paper")

Below is a PDF explorer that visualizes the flight network models used to illustrate each attendee's commute to the APA Annual Meeting for the 2018 New York City and 2019 San Francisco Annual Meetings. The third page shows a counterfactual scenario had the attendees who registered for the 2020 Philadelphia meeting actually attended; However, the 2020 meeting was canceled with a virtual substitute in the wake of the COVID-19 pandemic. The arcs measure the *distance as the crow flies,* or the *geodesic distance* between each attendee's origin and the Annual Meeting location. The width and intensity of the arcs is proportional to the number of people originating from a given location.

It may take some time for the PDF explorer to load, as these are large vectorized images. 

 {{< embed-pdf url="  /pdfs/APA Flight Netowrks.pdf" >}}

## Notes

If you are interested in viewing further visualizations or the analysis itself, there is a comprehensive repository containing all the R code used to generate the plots and model the attendee emissions available at my [GitHub.](https://github.com/Alec-Stashevsky/GAP-climate-research)

I would like to thank my coauthors, especially Dr. Josh Wortzel and Dr. Elizabeth Haase for the opportunity to participate in this important research.

I would also like to thank [GoClimate](https://www.goclimate.com/) for granting us access to their [Flight Emisions API.](https://api.goclimate.com/docs)

Please feel free to reach out with any questions
