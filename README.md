# Introduction
I analyzed the personalities of fifteen philosophers, operationalized by their [Big Five personality scores](https://cloud.ibm.com/docs/personality-insights?topic=personality-insights-models). Personality scores were calculated using [IBM's Watson Personality Insights API](https://www.ibm.com/watson/services/personality-insights/).

Philosophers were split into three groups, in terms of the fundamental type of ethics they endorsed: Virtue Ethics (_i.e_ character-based), Deontological Ethics (_i.e._ duty-based), and Utilitarian Ethics (_i.e._ consequence-based).

To view the entire analysis (including all visualizations, statistical tests, and additional explanatory text) please see the IPython Notebook [philosopher_personality_analysis](philosopher_personality_analysis.ipynb).

# Summarized Findings

The analysis indicated that there is no significant relationship between a philosopher's personality traits and their fundamental ethical position.  However, while there was good deal of in-group variation for virtue and deontological philosophers, utilitarian philosophers had quite similar personality traits.

# Visualizations

Here are some of the more interesting visualizations created in this analysis.

Radar charts showing each philosopher's personality score percentiles.

![Radar plot: virtue philosophers stacked](https://github.com/josh-hm/philosopher_personalities/plots/radar_virtue_stacked.svg)
![Radar plot: virtue philosophers individualized](https://github.com/josh-hm/philosopher_personalities/plots/radar_virtue_individual.svg)
<br>
![Radar plot: deontological philosophers stacked](https://github.com/josh-hm/philosopher_personalities/plots/radar_deontological_stacked.svg)
![Radar plot: deontological philosophers individualized](https://github.com/josh-hm/philosopher_personalities/plots/radar_deontological_individual.svg)
<br>
![Radar plot: utilitarian philosophers stacked](https://github.com/josh-hm/philosopher_personalities/plots/radar_utilitarian_stacked.svg)
![Radar plot: utilitarian philosophers individualized](https://github.com/josh-hm/philosopher_personalities/plots/radar_utilitarian_individual.svg)
<br>
<br>
<br>

A distance heatmap calculated using the pair-wise distance between philosophers in the 5-D personality trait space. It shows how different/close the philosophers are, both within and between the categories of ethic type.

![Heatmap: distance between ethics groups](https://github.com/josh-hm/philosopher_personalities/plots/distances_groups.svg)