Folders are named in the following format: vacancyRatio-NeighbourPreference-baseNeighbourSatisfaction
	Vacancy Ratio: % of land not empty
	Neighbour Preference: Preference for in-group neighbours (0->0, 0.5->50, 1->100)
	Base Neighbour Satisfaction: Satisfaction of agent with empty land as neighbour (0->0, 0.5->50, 1->100)

Conclusions:
1) Increased Vacancy Ratio decreases Segregation & Stability -> Agents need higher in-group preference to segregate & Achieve Stability -> illustrated by folders in VacancyRatioTest folder
2) Increased Base Neighbour Satisfaction has no measurable effect on segregation -> increase in satisfaction with empty space compensates for neighbour preference -> illustrated by folders in BaseNeighbourSatisfactionTest folder
3) Increased Neighbour Preference increases segregation until a certain threshold beyond which it just increases noise, 	because desired satisfaction will never be met
->Exact thresholds depend on Vacancy Ratio & Base Neighbour Satisfaction 
->illustrated by folders in NeighbourPreferenceTest folder
4)SchellingModelParametersEstimate folder contains best guess at parameters Schelling used

Example Sets:
Use whichever example set is most visually pleasing. They should each be able to demonstrate the respective point