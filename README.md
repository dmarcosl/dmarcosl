## Introduction

`hello_world.py`
```python
from typing import Tuple


class Meta(type):
    def __new__(cls, name, bases, attrs):
        return super().__new__(cls, name, bases, attrs)


class Bio(metaclass=Meta):
    name        : str = "Daniel Marcos"
    designation : str = "Software Engineer"
    company     : str = "Inditex"
    base        : str = "Spain"
    

class Stack(metaclass=Meta):
    languages   : Tuple[str, ...] = ("Python", "Java", "Typescript")
    databases   : Tuple[str, ...] = ("Mongo", "Redis", "PostgreSQL", "MySQL")
    misc        : Tuple[str, ...] = ("Flask", "Celery", "Scrapy",
                                     "Spring", "Maven", "Reactor Core",
                                     "Angular", "Docker", "AWS", "GCP")


class Social(metaclass=Meta):
    github      : str = "github.com/dmarcosl"
    linkedin    : str = "linkedin.com/in/dmarcosl"
```

## Technologies and Tools

### At work

![image](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=java&logoColor=white)
![image](https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white)
![image](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)
![image](https://img.shields.io/badge/SQL-005C84?style=flat-square&logo=mysql&logoColor=white)
![image](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)
![image](https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white)
![image](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![image](https://img.shields.io/badge/Docker-2CA5E0?style=flat-square&logo=docker&logoColor=white)
![image](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=Postman&logoColor=white)
![image](https://img.shields.io/badge/IntelliJ-000000.svg?style=flat-square&logo=intellij-idea&logoColor=white)


### At home

![image](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![image](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![image](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![image](https://img.shields.io/badge/Firebase-ffca28?style=flat-square&logo=firebase&logoColor=white)
![image](https://img.shields.io/badge/Kotlin-0095D5?&style=flat-square&logo=kotlin&logoColor=white)
![image](https://img.shields.io/badge/LaTeX-47A141?style=flat-square&logo=LaTeX&logoColor=white)
![image](https://img.shields.io/badge/Lua-2C2D72?style=flat-square&logo=lua&logoColor=white)
![image](https://img.shields.io/badge/Raspberry-A22846?style=flat-square&logo=Raspberry%20Pi&logoColor=white)
![image](https://img.shields.io/badge/Unity-100000?style=flat-square&logo=unity&logoColor=white)
![image](https://img.shields.io/badge/Debian-A81D33?style=flat-square&logo=debian&logoColor=white)

