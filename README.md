# Introduction
![Detailed infographic of my proposed nationwide congressional map.](/NationwideRedistricting.png)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Hello! In this repository, you will find a detailed and comprehensive analysis of what I believe to be the ideal configuration for the 435 single-member districts used by the United States House of Representatives, following the reapportionment of congressional districts based on the results of the 2020 Census. I have long believed that gerrymandering is one of the graver—and relatively under-discussed—threats to our democracy. Because the vast majority of Americans live in a state where reapportionment is controlled entirely by their state legislature, the current district map for the 118th Congress is rife with congressional districts that completely disregard common-sense redistricting principles such as proportionality, compactness, and preservation of communities of interest. This is not a particularly surprising phenomenon; it makes sense that politicians, when given free rein to do so, will use every tool at their disposal to ensure their own re-election or secure disproportionate majorities for their party.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In an effort to present an example of what good-faith congressional districts might look like, I have worked my way through every state and every precinct to propose alternative redistricting that demonstrates the principles that such work should aspire to. The maps that you will find in this repository are carefully and deliberately drawn. Every redistricting plan presented in this repository meets the basic criteria for legislative districts; that is, they are contiguous and equal in population. I have also taken care to ensure that my proposed plans are compliant with Federal criteria mandated by the equal protection clause of the Constitution as well as Section 2 of the Voting Rights Act. Each redistricting plan is also compliant with all state-level redistricting criteria—the specifics of which will be discussed in the relevant write-up for each map.

# Navigating this Repository

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;At this moment in time, this project is a work in progress. Though I have completed drawing each map for all 50 states (the final product for which can be seen on my national map), there still remains a significant amount of work to be done. Over the course of the next several months, I will upload write-ups (and accompanying graphics) for each state as I complete them.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;At the top of this folder, you will find this introduction, as well as a nationwide map showing how my set of hypothetical congressional maps would fare in the 2020 presidential election. Below that, you will find one folder for every state, each containing the completed shapefile of my redistricting proposal as well as a detailed .csv file containing extensive election and demographic data for that state’s respective districts. As they are completed, I plan to upload each individual write-up and graphic to that state’s respective folder.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In each write-up, I will discuss at length the various factors and philosophies that are at play when drawing congressional maps in that state. I will, to the best of my ability, attempt to explain and defend why I have drawn each map the way it is configured. Redistricting is an infamously convoluted process, and it is important to justify the specific configuration of each district—especially considering the millions of mathematically possible district arrangements. Naturally, not every district is created equal! While I will give as much commentary as I feasibly can, some districts will by their very nature merit only a very short discussion (for example, states that have a singular at-large congressional district). Conversely, some regions will elicit much longer discussion, owing to factors such as long-standing legal battles, significant political realignment in recent years, or considerable contention among mapmakers regarding the ‘ideal’ configuration of a district.

# Qualifications

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;My scathing commentary regarding the current state of affairs begs the question; why am I qualified to opine on the matter? I will concede that I am not a redistricting ‘expert’ by any means. While I do consider myself to be very knowledgeable on the topic, I acknowledge many individuals are leagues more qualified to speak on the topic than I am. That being said, a tremendous amount of time and effort has gone into this project. Beyond requiring detailed knowledge of both national and state-level redistricting criteria, I spent countless hours carefully researching the political geography and relevant communities of interest of every state in the country. In addition to this, the infographic maps presented in each individual write-up, generated with GIS software and Excel, represent dozens more hours of work.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;As stated previously, redistricting is an incredibly contentious process, not only from a political perspective but also through a cartographic lens. No matter how carefully one draws a district, someone will always think they could do a better job themselves. I do not claim to be the arbiter of what constitutes a fair map; depending on how one prioritizes different redistricting criteria, there are myriad maps that can be drawn for any given state, all of which can be considered ‘fair’. All of that said, I will put my maps up against anyone’s from a perspective of fairness and elegance.

# My Redistricting Philosophy

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;As stated above, there is no objectively correct way to draw a congressional map. Depending on which cartographic factors one prioritizes, a map can have countless possible configurations, all of which are equally valid. In this section, I will outline which cartographic factors I believe to be the most important and my reasons for ranking them the way I have. In doing so, I hope to inform my future analysis of each state-specific map. From a general standpoint, my priorities when creating congressional maps are as follows:
1. Preserving communities of interest (henceforth COIs) such that their voice is adequately represented in congress. This also includes any decisions that may be made along racial lines, as race can demonstrably be a compelling COI in its own right (Taking care, of course, to ensure that racial considerations do not predominate).
2. Partisan fairness; ensuring that when possible, a map is fair to both political parties and that each side receives a share of seats roughly proportional to their share of the vote. Unfortunately, this is not always possible.
3. Compactness; ensuring that districts are relatively compact. Though some districts that are presented in this repository may have odd shapes, these are never created without a compelling reason.
4. Avoiding splitting counties, cities, or municipalities unnecessarily; while it is generally a good rule of thumb to avoid splitting civil divisions between districts, it is also important to keep in mind that these lines are not always representative of communities of interests.
5. Competitiveness; evenly-split districts are good to have on any map. However, they should only exist in areas that are themselves evenly split politically. In other words, it is bad practice to combine deep-blue and deep-red areas to create a competitive district.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;While applying these standards to the map-making process does help illuminate many of my specific decisions, it is crucial to remember that they cannot perfectly explain the specific configuration of every given district. As I post my state-by-state write-ups, I will provide more individualized commentary. My goal in posting this generalized philosophy is to contextualize the mindset in which these maps were drawn.

# Methodology
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;All of the maps presented in this repository were created using the free and open-source <a href="https://davesredistricting.org/maps#home" target="_blank">Dave’s Redistricting App</a> (DRA 2020). Likewise, all election and demographic data shown in this project were compiled by the DRA 2020 team. If you would like to read more about the sourcing and manipulation of this data on the website, you can do so <a href="https://davesredistricting.org/maps#aboutdata" target="_blank">here</a>. After maps were created using this software, they were then exported to QGIS, where they were arranged in infographic format. For infographics that display election results by census tract, shapefiles and census block-level population data were sourced from the Census Bureau. I then used probabilistic data disaggregation to estimate results at the block level before reaggregating those results by census tract. This project would not have been possible without the amazing work of the DRA 2020 team, as well as other aggregators of election data such as the Harvard Voting and Election Science Team.
