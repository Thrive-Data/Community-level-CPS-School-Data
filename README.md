# Community-level-CPS-School-Data

## What this code does?
This repository is for creating static maps in R showing the geographic distribution of community-level graduation rate, college enrollment rate, college persistence rate, college completion rate, and the Postsecondary Attainment Index (an estimate of the proportion of freshman that will have a college degree within 10 years).

## Why is this useful?
Typically, publically available data on educational outcomes are either at the district-level or at the school-level; see Chicago Public Schools (CPS) data [here](https://www.cps.edu/about/district-data/). But at CPS (and many other large urban school districts), students regularly attend schools that are outside of their community. This means that if we only have school-level outcomes, we can only imperfectly attribute them to the community of the school. This means 1) we are limited to an imperfect estimate of community level outcomes like graduation rate by aggregating and taking weighted means of schools within that community (meaning we have an imperfect and potenitally biased meansure); and 2) this limits our ability to understand correlates of community-level outcomes. 

## Who is this useful for?
This repository is likely most useful to data analysts working in the nonprofit space in Chicago. Though I hope this can be a resource for data analysts in other cities and can be used as a resource for creating maps using ```tmap```.

## Data Source and Definitions
Data on community-level educational outcomes are from [To&Through](https://toandthrough.uchicago.edu/tool/cps/comm/2021/#/milestones) and data definitions can be found [here](https://toandthrough.uchicago.edu/tool/cps/comm/2021/definitions/).

The community area shapefile can be on the [Chicago Data Portal](https://data.cityofchicago.org/Facilities-Geographic-Boundaries/Boundaries-Community-Areas-current-/cauq-8yn6).

# About

Thrive Chicago is a dedicated group of individuals who are committed to collaborative work, creative problem solving, and breaking down systemic barriers to achieve equity for young people and communities. More information about us and our work can be found [here](https://thrivechi.org/).

Questions about the code or other data-related inquiries can be sent to David Krosin at dkrosin@thrivechi.org.

