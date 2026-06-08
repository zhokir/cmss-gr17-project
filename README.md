# Project Definition
### This project demonstrates a standard Schelling model with the additional constraints of unequal relocation using different options.
### The following research question will be answered with this project:
Does unequal mobility between social groups increase final segregation, convergence time, satisfaction inequality and relocation constraints in a Schelling-type residential model?

#### This research question  is further split up into these sub questions:
* RQ1: Does lower mobility for one group increase the final residential segregation index?
* RQ2: Does lower mobility for one group increase the number of steps needed to reach equilibrium?
* RQ3: Does lower mobility for one group increase the satisfaction gap between the high-mobility and low-mobility groups?
* RQ4: Does lower mobility for one group increase failed relocation attempts for that group?
* RQ5: Does a higher tolerance threshold strengthen the effect of unequal mobility on convergence time and satisfaction inequality?
* RQ6: Does restricted destination access, such as radius-limited movement, increase the effect of unequal mobility on convergence time and satisfaction inequality?

# Project Structure
The main directory consists of the code and output folders and the project report **report.pdf** written in latex.
In the code folder, there is a single jupyter file named **project.ipynb** containing all the code necessary to create the images and models as described in the report. The output folder contains all plots created by the jupyter file which are used in the report

# Model Definition
The model follows the standard schelling model, with addition of unequal constraints such as different mobility chances for the groups, groups only being able to relocate in a specific radius and different threshold for cell satisfaction. All of these combined provide a new view on the existing schelling model papers.