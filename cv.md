# rsschool-cv
# Koshenov Batyrkhan
### Contact information:
**Phone:** +7708 855 8216  
**E-mail:** someday127@gmail.com  
**Discord:** @kbatyr
***
### About myself:
There's nothing yet...
### Skills and Proficiency:
* Go
* HTML5, CSS3
* Git, Github
* Docker
### Code example:
*This example implements the **split** function of standard package of Go library:*   
``` func Split(s, sep string) []string {
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
### Education: