### `Hello World!`

```python
class DanielAddison:
    def __init__(self):
        self.name = "Daniel Addison"
        self.role = "Technical Operations Analyst"
        self.workplace = "Sony Interactive Entertainment"
        self.base = "Los Angeles, CA"
        self.description = """Welcome! I'm an IT and Cloud Operations professional based in 
        Los Angeles. I specialize in cloud infrastructure, system automation, and operational 
        health—keeping major digital systems running seamlessly behind the scenes. Whether I'm 
        managing bare metal lifecycles, optimizing platforms for high availability, or building 
        developer tools, my goal is to deliver reliable, scalable tech experiences that support 
        people and businesses every day."""

        self.languages = ['Python', 'JavaScript', 'Java', 'Bash', 'SQL']
        self.databases = ['PostgreSQL', 'MySQL', 'MongoDB', 'Redshift']
        self.cloud_and_devops = [
            'AWS (EC2, S3, RDS, Lambda, CloudFormation)',
            'Terraform', 'Docker', 'Kubernetes', 'Ansible', 'AWX',
            'CI/CD Pipelines', 'Grafana Monitoring', 'Linux Administration'
        ]
        self.ongoing = [
            'AWS Solutions Architect - Associate',
            'AI-Driven Workflows (Cursor, Claude Code)',
            'Cloud Gaming Infrastructure & Bare Metal Operations'
        ]

        self.linkedin = 'danieladdsn'
        self.website = 'https://danieladdsn.com'

    def say_hi(self):
        print("Thanks for dropping by! Hope you find some of my work interesting.")

me = DanielAddison()
me.say_hi()
```
