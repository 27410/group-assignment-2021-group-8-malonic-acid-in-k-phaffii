[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/27410/group-assignment-2021-group-8-malonic-acid-in-k-phaffii/main)

# 27410 - Group assignment - Group 8 - _Komagataella pfaffii_ producing malonic acid

> Dear students, thank you for accepting the group assignment. Please fill in the
> requested information below and above ([Group Number] and [TITLE]) and remove this quoted part before submission (everything prepended with a >).
> Please also replace `[PUT-YOUR-REPOSITORY-HERE]` up in the first line 👆 with the name of your repository here on GitHub.
> That way someone can click on the Binder badge icon and open your project in Jupyter lab to explore it.
> For this to work you will also have to keep `requirements.txt` up to date (by running `pip freeze > requirements.txt`).
> Furthermore, this will only work if you decide to make your repository public (which you can do under Settings -> Options),
> which I would encourage you to do – up to you. A lot of good science happens out in the open these days.
> Good luck!

>Summary: Describe the overall aim of your project and what you have achieved.
>Overvie: Describe how your project is organized.
## Project summary (<300 words)
This project aims to improve the genome-scale model (GSM) of _Komagataella phaffii_ for the production of malonic acid from methanol. Tomàs-Gamisans et al developed the GSM iMT1026.V3 in 2017 for better predictions of growth in methanol. The heterologous pathway to produce malonic acid was added successfully. Furthermore, the model is used to calculate the maximum yield and calculating phenotypic phase planes. 

## Project overview
The main page of the repository contains the Report.ipynb notebook, which contains the main report of this project.
The folders are structured in the following manner

├── img                 # Images used for the Report
├── models              # calculated models for this report
├── reports             # Memote reports of the src models
├── src                 # Source models which were tested
│   ├── gen             # Models generated by us
│   ├── lit             # Models from the literature
