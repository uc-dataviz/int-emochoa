Dashboard Write-up
================
Erin M. Ochoa<br>
2018 May 18

<p align="justify">
<a href=http://people.cs.uchicago.edu/~emo/ClimateViolence><i>Violence: The Roles of Climate and Disadvantage</i></a> presents some of the results from my thesis project, in which I empirically classified climate regions, detected the most appropriate number of such regions, and used the resulting map in an investigation of regional differences in violent crime rates. In those analyses, I focused on the role of disadvantage (an index created from six variables: Percent secondary sector low-wage jobs, jobless rate for working age population, percent professionals & managers \[reverse-coded\], percent female-headed households, percent college graduates \[reverse-coded\], and poverty rate), as this condition has previously been identified as an important factor that explains neighborhood differences in violent crime (Peterson & Krivo, 2010, <i>Divergent Social Worlds</i>). I defined seven different models—four linear, one by regimes, and two spatial—to assess the impact of tract- and city-level covariates as well as differences across climate regions.
</p>
<p align="justify">
The dashboard incorporates results from five of the models—two linear (A & B), one by regimes (C), and two spatial (D & E). Models A & B show that under a linear model, not only does the level of violent crime vary by region but that the role disadvantage plays in such crimes also varies by region. Maps for models C, D, and E visualize coefficients for a subset of regions; each map highlights the regions for which that model is correctly specified. Together, the results indicate that climate moderates the relationship between disadvantage and violent crime, with disadvantage driving violence in some regions but not others.
</p>
<p align="justify">
I selected this format because it is linear, yet moves at the user’s pace. Advancing from one slide to the next is intuitive, and the self-directed navigation allows the user to go back and forth between slides as necessary, exploring the region-specific coefficients for each model along the way.
</p>
<p align="justify">
The interactivity in the dashboard is constrained to two main functions:<br> —The user chooses when to advance to the next slide (or jump back to an earlier slide), and<br> —The user can hover the mouse pointer over each climate region in each of the regional maps to learn the regional value of the coefficient visualized in that map.
</p>
<p align="justify">
The first function, which requires that the user exercize self-directed navigation through the dashboard, allows the user to spend as much or as little time as desired on each slide. This is contrast to the <a href=https://fivethirtyeight.com/features/gun-deaths>FiveThirtyEight Gun Deaths in America visualization</a>, which, though it has a similar navigation style, employs text that fades in, which slows the speed of navigation and may frustrate some users.
</p>
<p align="justify">
The second function allows the user to get additional information (the precise coefficient visualized in the current map) for each region in each of the coefficient maps. This is an important feature of the visualization because some of the maps have bins with a large range and providing the value of each coefficient via a mouse-over improves the efficiency of data communication while preserving aesthetics.
</p>
