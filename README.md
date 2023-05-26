# Suitable_Jaguar_Habitat



The primary objective of this project is to understand the Jaguar habitat along the Guatemalan and southern Mexico border. With limited knowledge of ecology and Jaguars, I embarked on comprehending their ecological niche, behavioral patterns, and environmental relationships. To aid Dr. Gerardo Ceballos in his jaguar conservation efforts, I began developing a predictive model to identify areas susceptible to deforestation and urbanization. The aim is to create a visual representation of strong predictive relationships that define suitable jaguar habitats.

Through my research, I have gained extensive knowledge about these magnificent creatures, almost feeling acquainted with a particular jaguar tagged with a GPS for nearly a year. I affectionately named him Tecun, after a Guatemalan king. Tecun's vast territory spans both sides of a man-made road, serving as a sentinel overlooking the clearings, farms, and bustling streets of nearby villages. Although he remains close during the day, he ventures far and wide throughout the weeks, exhibiting consistency with an unpredictable nature—truly a vigilant king.

Aware of the emotional reactions often associated with animal welfare concerns, I aimed to prioritize data-driven actions over impulsive responses. These are complex issues, and within these regions, people make decisions to protect their livestock and provide for their families. By enhancing the effectiveness of conservationists' efforts, I hope to foster a more symbiotic relationship between the forces of the modern world.

In this research, I will employ a Convolutional Neural Network and explore the use of a Maxent model in future work. Kimberly Craighead's paper on this topic, available at [paper link](https://link.springer.com/article/10.1007/s10980-021-01335-2#data-availability), highlights the underutilization of such methods by ecologists. By presenting my findings in a non-traditional research format, I seek to demystify the process and encourage further exploration. Moreover, I invite questions and discussions to expand the potential applications of this model.

<img width="865" alt="Screen Shot 2023-05-26 at 3 42 27 PM" src="https://github.com/ThomasAbeyta/Suitable_Jaguar_Habitat/assets/99691576/8c2122de-c8af-4d17-8b07-116cef38846e">
* *This image shows a heatmap of the Jaguars movement over a week and the plotted points are all of the points of the course of a year in chronolgical order from white to dark blue. 

I was able to produce over 3400 observations to feed my model and yielded a 92% accuracy which can be tested across the the region. In further work I plan to improve my feature set by disecting and incrementally assembling the DataFrame. Then I will apply an overlay that will gradient the map across the region (184,548 sq/km)to illustrate areas of high to low suitablitly for jaguars. 





