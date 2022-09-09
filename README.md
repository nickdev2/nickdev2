```py
class Nick:
  def __init__(self):
    self.Name = "Nick"
    self.Age = 13
    self.Discord = "flow#0333"
    self.Role = "Student"

  def welcomeUser(self):
    print(f"""Hey there! I'm {self.Name}, and I'm {self.Age} years old. 
              I'm currently a {self.Role}. 
              If you need to contact me, add me on Discord! ({self.Discord})""")
    
nick = Nick()
nick.welcomeUser()
```
