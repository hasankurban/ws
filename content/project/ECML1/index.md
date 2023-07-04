---
date: "2023-06-20T00:00:00Z"
external_link: ""
image:
  caption: 
  focal_point: 
#links:
#- icon: 
#  icon_pack: 
#  name: 
#  url: 
#slides: 


summary: Making Fantasy Leagues More Real by Adding Team Chemistry
tags:
- data-mining 
- nba-fantasy-league
-  python-flask 
- feature-engineering
-  scaling-statistics

title: More Real Fantasy Leagues
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---
Fantasy Sports has a current market size of 23B and is expected to grow more than 84B in less than a decade. The intent is to create virtual teams that somehow reflect what would happen if the players actually played. Using individual player stats, models predict an outcome. But fans are left wanting more. To achieve a more realistic outcome (something more than just statistics), aspects of what makes live teams win need to be included: (1) transforming stats to reflect the relative importance with respect to a position; (2) team chemistry (TC). In this work, we show a novel characterization of relative position statistics and a new description of TC. Drawn from the NBA's API, we form a data set to determine whether a fantasy team makes the playoffs using over two dozen features, including TC. Our system has over 100 models competing to be the best predictor with compelling results. To allow users to use this more realistic fantasy team model, we offer a web service (continually updating from the API) and inspect not only virtual teams and TC but simulate match-ups with existing 2023 NBA teams and visualizations helping to improve team creation. Our web service can be accessed at https://dalkilic.luddy.indiana.edu/fantasyleague/, and the source code can be found in our https://github.com/gany-15/nbafan.