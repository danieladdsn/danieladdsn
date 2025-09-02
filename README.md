### `Hello World!`

```python
class DanielAddison:
    def __init__(self):
        self.name = "Daniel Addison"
        self.role = "Solution Architect"
        self.workplace = "Yum! Brands"
        self.base = "Los Angeles, CA"
        self.description = """I'm an IT professional with a degree in Information Technology and Systems
        from Marist College. My background spans software engineering, cloud infrastructure, and DevOps,
        and I'm now focused on Solution Architecture. I design and evaluate secure, scalable, and
        cost-effective systems, while leveraging my hands-on experience in cloud technologies.
        I’m passionate about bridging technical and business perspectives, guiding design decisions,
        and contributing to impactful projects that deliver long-term value."""

        self.languages = ['Python', 'Java', 'JavaScript', 'Bash']
        self.databases = ['MySQL', 'MongoDB', 'PostgreSQL', 'Firebase', 'Supabase']
        self.misc = [
            'Cloud Architecture', 'Well-Architected Framework',
            'High Availability & Scalability', 'Cost Optimization',
            'Systems Design', 'Security Best Practices',
            'CI/CD Strategy', 'Multi-Cloud Solutions'
        ]
        self.ongoing = [
            'Solution Design', 'AWS Architecture',
            'Enterprise Cloud Patterns', 'Cloud Governance'
        ]

        self.twitter = 'danL'
        self.linkedin = 'danieladdsn'

    def say_hi(self):
        print("Thanks for dropping by. I hope you find some of my work interesting.")

me = DanielAddison()
me.say_hi()
```
