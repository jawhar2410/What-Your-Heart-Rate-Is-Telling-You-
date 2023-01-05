# Projet Analyse de donnee
# What Your Heart Rate Is Telling You 

-----------------------------------------------------
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jawhar2410/What-Your-Heart-Rate-Is-Telling-You-/main?labpath=notebook.ipynb)
## presentation du projet
What Your Heart Rate Is Telling You about your heart



## dataset
age	sex	cp	trestbps	chol	fbs	restecg	thalach	exang	oldpeak	slope	ca	thal	class
<int>	<int>	<int>	<int>	<int>	<int>	<int>	<int>	<int>	<dbl>	<int>	<int>	<int>	<int>
1	63	1	1	145	233	1	2	150	0	2.3	3	0	6	0
2	67	1	4	160	286	0	2	108	1	1.5	2	3	3	2
3	67	1	4	120	229	0	2	129	1	2.6	2	2	7	1
4	37	1	3	130	250	0	0	187	0	3.5	3	0	3	0
5	41	0	2	130	204	0	2	172	0	1.4	1	0	3	0

## bibliotheque utilise

* pandas
<img src="https://seeklogo.com/images/P/pandas-logo-776F6D45BB-seeklogo.com.png">  

* matplotlib
<img src="https://miro.medium.com/max/1370/1*BLx1p0j0zVhPf_VC-OTwCQ.png">  

## conclusion 
Bien que notre modèle ait une précision globale de 0,71, certains cas ont été mal classés, comme indiqué dans la matrice de confusion. Une façon d'améliorer notre modèle actuel consiste à inclure d'autres prédicteurs pertinents de l'ensemble de données dans notre modèle, mais c'est une tâche pour un autre jour
