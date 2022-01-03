# [rsschool-cv](https://github.com/kbatyr/rsschool-cv)
# Koshenov Batyrkhan
### Contact information:
**Phone:** +7708 855 8216  
**E-mail:** someday127@gmail.com  
**Discord:** @kbatyr
***
### About myself:
Hi everyone! My name is Batyrkhan, I'm 25 years old and from Kazakhstan, Nur-Sultan. Now I'm studying at **alem** programming school based on the international education system called [01 Edu System](https://01-edu.org/).  
***
### Skills and Proficiency:
* Go
* HTML5, CSS3
* Git, Github
* Docker
***
### Code example:
*This example implements the **split** function of Go language standard library.*  
```
func Split(s, sep string) []string {
	if sep == "" {
		for _, ch := range s {
			res = append(res, string(ch))
		}
	} else {
		for i := 0; i <= len(s)-len(sep); i++ {

			if s[i:len(sep)+i] == sep {
				s = s[:i] + " " + s[len(sep)+i:]
			}
		}

		var res []string
		var word string
		for _, let := range s {
			if let != ' ' {
				word += string(let)
			} 	else {
				res = append(res, word)
				word = ""
			}
		}
		if word != "" {
			res = append(res, word)
		}
	}
	return res
}
```
***
### Education:
* [Eurasian National University](https://enu.kz/ru/), Information Technologies, 2013-2017  
* [Alem](https://alem.school/) programming school, Kazakhstan, Nur-Sultan 2021  
***
### Language skills:
* Kazakh: native speaker
* Russian: native speaker
* English: B1  
