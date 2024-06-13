### `Hello World!`

```python
class DanielAddison:
    def __init__(self):
        self.name = "Daniel Addison"
        self.role = "Cloud Operation Engineer"
        self.workplace = "Mission Cloud Services"
        self.base = "Los Angeles, CA"
        self.description = """I'm a graduate in Computer Science from Marist College.
I'm a passionate learner who's always willing to work across technologies and domains.
I love to explore new technologies and leverage them to solve real-life problems.
Currently, I'm working on improving my knowledge of Data Structures and Algorithms."""

        self.languages = ['Python', 'Java', 'JavaScript', 'Bash']
        self.databases = ['MySQL', 'MongoDB', 'PostgreSQL']
        self.misc = ['AWS', 'Docker', 'Kubernetes', 'Terraform']
        self.ongoing = ['Full Stack Development']

        self.twitter = 'danL'
        self.linkedin = 'danieladdsn'

    def say_hi(self):
        print("Thanks for dropping by. I hope you find some of my work interesting.")

me = DanielAddison()
me.say_hi()

```