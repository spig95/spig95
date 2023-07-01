### About me 🖖

```python
class SoftwareEngineer(Human):
    def __init__(self, name, expertise, hobbies, coding_skills):
        super(SoftwareEngineer, self).__init__(name, expertise, hobbies)
        assert isinstance(coding_skills, list) and len(coding_skills) > 0
        self.coding_skills = coding_skills

    def react_to_non_working_code(self):
        print("Strange, it works on my machine!")


myself = SoftwareEngineer(
    name="Nicola",
    expertise=[
        "Machine learning",
        "Reinforcement learning"
        "Data science",
        "DevOps, MLOps, CI/CD, agile",
    ],
    hobbies=[
        "Table tennis",
        "Diabolo juggling",
        "Reading",
        "Beach volley",
    ],
    coding_skills=[
        "Python",
        "C#",
        "HTML, CSS, JS",
        "C++",
        "SQL",
    ]
)
```

### Projects

Here you can find a list of some of the projects I have worked on (the ones that I could publish on Github).

| Year          | Repo          | About         |
| ------------- | ------------- | ------------- |
| 2023  | [Scrapsters](https://github.com/skyZcoding/EcoMania-Backend) | Mobile app to reward for sustainable shopping. Winner of the Migros challenge at Hackzurich 2023. |
| 2023  | [PizzaVsCats](https://github.com/spig95/pizza_vs_cats)  | You have five cards in your hand; each one could represent anything. Which one is the best!? |
| 2022  | [NoClip](https://github.com/VDP-noclip/noclip)  | An experimental game in which you "noclip" the environment to solve puzzles. |
| 2022  | [Review tracker](https://github.com/spig95/review-tracker)  | Django project to scrape online reviews and show the average evolution over time. |
| 2020  | [Riocontra translator](https://github.com/spig95/riocontra-translator)  | A useful translator if you happen to meet the 'uncle-of-the-road' in the streets of Milan. |
| 2019  | [Stochastic Modeling of Pollutant Transport in Aquifers](https://github.com/spig95/Project_Stochastic/blob/master/Submission/Report.pdf)  | We modeled groundwater particles trajectories as a random-motion and computed their probability of polluting a well. We compared different Montecarlo techniques with a deterministic approach based on PDEs. |
| 2018  | [Street Detection from Aerial Imagery](https://github.com/spig95/ML_project_2)  | Given a satellite image of a city, we trained a convolutional neural network (CNN) to identify and highlight streets. |

### Get in touch

[![Linkedin](https://i.stack.imgur.com/gVE0j.png) LinkedIn](https://www.linkedin.com/in/ischia95/)
