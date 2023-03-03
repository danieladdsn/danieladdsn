### `Hello World!`

```JavaScript
class DanielAddison {
  constructor() {
    name = "Daniel Addison";
    role = "Cloud Operation Engineer";
    workplace = "Mission Cloud Services";
    base = "Los Angeles, CA";
    description = `I'm a graduate in Computer Science from Marist College. 
      I'm a passionate learner who's always willing to work across technologies and domains. 
      I love to explore new technologies and leverage them to solve real-life problems. 
      Currently, I'm working on improving my knowledge of Data Structures and Algorithms.`;
    
    languages = ['Python', 'Java', 'JavaScript', 'Bash'];
    databases = ['MySQL', 'MongoDB', 'PostgreSQL'];
    misc = ['AWS', 'Docker', 'Kubernetes', 'Terraform'];
    ongoing = ['Full Stack Development'];
    
    twitter = 'danL';
    linkedin = 'danieladdsn';
  }

  sayHi() {
    console.log(
      'Thanks for dropping by. I hope you find some of my work interesting.'
    );
  }
}

const me = new DanielAddison();
me.sayHi();

```
