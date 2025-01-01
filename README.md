<img src="https://i.imgur.com/bjglhLZ.jpeg" min-width="400px" max-width="400px" width="400px" align="right" alt="Gopher coding">

```go
package main

import "github.com/arthurmvo/profile"

func main() {
	bio := Bio{
		Name:     "Arthur Martins",
		Title:    "Full-Stack Web Developer",
		Company:  "Salsa Technology",
		Location: "Florianópolis, BR",
	}

	skills := Skills{
		Languages:  []string{"Go", "JavaScript", "Python", "TypeScript", "Java", "C/C++"},
		Frameworks: []string{"React", "Angular", "React Native", "Flask", "Django", "Express"},
		Databases:  []string{"MongoDB", "PostgreSQL", "MySQL", "SQL Server", "DynamoDB"},
		Tools:      []string{"Git", "Docker", "AWS", },
	}

	profile.Display(bio, skills)
}
```

[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:arthurmvo@gmail.com)  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arthurmvo)  [![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=github&logoColor=white)](https://github.com/arthurmvo)
