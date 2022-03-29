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

![image](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![image](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![image](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)
![image](https://img.shields.io/badge/SQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![image](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![image](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![image](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![image](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)
![image](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white)
![image](https://img.shields.io/badge/IntelliJ-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white)


### At home

![image](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![image](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![image](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![image](https://img.shields.io/badge/Firebase-ffca28?style=for-the-badge&logo=firebase&logoColor=white)
![image](https://img.shields.io/badge/Kotlin-0095D5?&style=for-the-badge&logo=kotlin&logoColor=white)
![image](https://img.shields.io/badge/LaTeX-47A141?style=for-the-badge&logo=LaTeX&logoColor=white)
![image](https://img.shields.io/badge/Lua-2C2D72?style=for-the-badge&logo=lua&logoColor=white)
![image](https://img.shields.io/badge/Raspberry-A22846?style=for-the-badge&logo=Raspberry%20Pi&logoColor=white)
![image](https://img.shields.io/badge/Unity-100000?style=for-the-badge&logo=unity&logoColor=white)
![image](https://img.shields.io/badge/Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white)

