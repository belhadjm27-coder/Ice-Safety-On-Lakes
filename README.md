# Ice-Thikness Prediction On Trout Lake


## Background 
Creating an AI-powered application that estimates ice thickness to help users determine when to start and finish using the lake in winter and spring, respectively. Machine learning will analyze Weather Canada data to produce highly accurate ice-thickness predictions for Trout Lake through a Python program that integrates thermodynamic equations.


## Data and AI Techniques
This project aims to accurately predict ice thickness in Trout Lake (46.31° N, 79.34° W), thereby solving the mystery of when to safely access an ice-covered lake in the wintertime. My primary goal is to keep my community safe during winter activities on the lake, such as ice fishing and cross-country skiing. This can be efficiently achieved through education. Despite the best efforts of local authorities, such as the police and fire departments, to monitor ice development and guide the public, there are still deaths. Therefore, education through an AI application dedicated to this issue proves very useful. To lessen the challenges faced by lake users each year, my project aims to predict ice thickness in my community. Each year, people in my community suffer losses due to ice deterioration, and this AI-based application will highlight factors beyond temperature that influence ice growth so that people will take them seriously.


## How is it used
Everyone in the community looks forward to using the lake during winter. I am mainly excited about fishing, scientists gathering samples, athletes cross-country skiing, walkers, police, and firefighters. This group can access the app on their tablets or smartphones, which displays the ice thickness at their exact location. The app relies on a trained machine learning (ML) model based on credible sources like Weather Canada, providing two outputs: 1) ice thickness in inches, and 2) a safety warning for lake access. Whenever Weather Canada updates its database, the app automatically refreshes, runs the learning process in the background, and executes Python-based code to generate new predictions. Additionally, the app collects real-time feedback from users who challenge or confirm the output. For example, if users remove a piece of ice, take a picture, or share the actual ice thickness, the app incorporates this input into its reinforcement learning (RL) system. The app then uses convolutional neural networks (CNN) to analyse, compare, store, and code the images, matching them to previous outputs or producing new predictions. At this point, the app operates at full learning capacity.


## Challenges
This project relies on a system of thermodynamic equations that cannot account for ice growth near the shoreline, as the lake’s external parameters have a greater impact on the ice than the lake’s environment itself. This means that this ML-based app would perform well under natural weather conditions, but not when auxiliary factors, such as atmospheric pollution, are involved, since they can cause the ice to weaken even when it appears thick. Including too many variables may lead to overfitting the AI-based app, resulting in potentially dangerous outputs.


## Acknowledgments
* Lake Ice - [Home](http://lakeice.squarespace.com/)
* Ice physics for recreational ice-users : some thermal and mechanical properties of natural ice covers - [ISBN 9789175751627 | Studentapan](https://www.studentapan.se/kurslitteratur/ice-physics-for-recreational-ice-users-some-thermal-and-mechanical-properties-of-natural-ice-covers-9789175751627)
* Freezing of Lakes and the Evolution of Their Ice Cover - https://link.springer.com/book/10.1007/978-3-031-25605-9 
* Thin Ice Growth - https://static1.1.sqspcdn.com/static/f/572109/18056158/1336339358653/thin+ice+growth.pdf?token=jo%2FdOCMqpWd%2B2XWZxJWWt7DhFdM%3D
* Heat of Fusion - an overview | ScienceDirect Topics - https://www.sciencedirect.com/topics/earth-and-planetary-sciences/heat-of-fusion
* Deep Learning Model to Predict Ice Crystal Growth - PMC - https://pmc.ncbi.nlm.nih.gov/articles/PMC10375069/
