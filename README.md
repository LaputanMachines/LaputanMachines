<h2> Hi, I'm Michael Bassili <img src="https://media.giphy.com/media/mGcNjsfWAjY5AEZNw6/giphy.gif" width="50"> I Develop Software For Money</h2>

```python
#!/usr/bin/env python3
#-*- coding: utf-8 -*-

class MichaelBassili: 
    
  pronouns   = "he/him"
  profession = "devops"
  hobbies    = ["gamedev", "music", "art"]
  languages  = ["python", "c", "golang", "groovy", "html/css"]
  tools      = ["jenkins", "ansible", "terraform", "aws", "zabbix"]

  def get_summary(self):
      summary_string = "Hi! I'm Michael ({}) and I write software for money".format(self.pronouns)
      summary_string += "\n\t- I'm profficient with: {}".format(self.tools)
      summary_string += "\n\t- I've used the following languages: {}".format(self.languages)
      summary_string += "\n\t- In my spare time, I like work on: {}".format(self.hobbies)
      summary_string += "\nRight now I work in {0} and I develop games on the side".format(self.profession)
      print(summary_string)

if __name__ == '__main__':
  MichaelBassili().get_summary()
```

My name is Michael, and I'm many things. I work a day-job as a devops engineer. I moonlight as a drummer, [journalist](https://muckrack.com/michaelbassili), writer, and [game developer](https://aquinasgames.ca/). If you want to hire me to do one of these things, shoot me an email! Otherwise, feel free to browse my GitHub profile. I also have a [LinkedIn](https://www.linkedin.com/in/michael-bassili/) profile for networking-purposes, but I rarely interact with it. You can see some of the code I've written in GitHub. My [Twitter](https://twitter.com/michaelbassili) account is reserved for journalism.

[![Awesome Badges](https://img.shields.io/badge/Twitter-@MichaelBassili-blue.svg)](https://twitter.com/michaelbassili) [![Awesome Badges](https://img.shields.io/badge/LinkedIn-MichaelBassili-purple.svg)](https://www.linkedin.com/in/michael-bassili/)
