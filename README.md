```python
@dataclass
class Contact:
  name: str
  address: str

@dataclass
class Developer:
  name: str
  country: str
  pronoums: str
  job_title: str
  years_experience: int
  contacts: list[Contact]
  
  def greet(self):
    print(f"Hi there, I'm {self.name} ({self.pronoums}) from {self.country}! 👋")
    
  def experience(self):
    print(f"I'm a {self.job_title} with {self.years_experience} years of experience 🚀")
  
  def contact_me(self):
    print("You can reach me on 📫")
    for contact in self.contacts:
      print(f"{contact.name}: {contact.address}")
  
me = Developer(
  name="Lucas",
  country="Brazil",
  pronoums="he/him/his",
  job_title="Senior Software Engineer",
  years_experience=7,
  contacts=[
    Contact(name="Email", address="lucascbernardes@live.com"),
    Contact(name="LinkedIn", address="https://linkedin.com/in/lucascbernardes/?locale=en_US"),
    Contact(name="Website", address="https://lucascb.github.io"),
  ]
)

me.greet()
# Hi there, I'm Lucas (he/him/his) from Brazil! 👋

me.experience()
# I'm a Senior Software Engineer with 7 years of experience 🚀

me.contact_me()
# You can reach me on 📫
# Email: lucascbernardes@live.com
# LinkedIn: https://linkedin.com/in/lucascbernardes/?locale=en_US
# Website: https://lucascb.github.io

```

### Skills:  

<code><img height="32" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/python/python.png" alt="Python"/></code>
<code><img height="32" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png" alt="Javascript"/></code>
<code><img height="32" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/clojure/clojure.png" alt="Clojure"/></code>
<code><img height="32" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/typescript/typescript.png" alt="Typescript"/></code>
<code><img height="32" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/nodejs/nodejs.png" alt="Nodejs"/></code>
<code><img height="32" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/django/django.png" alt="Django"/></code>
<code><img height="32" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/react/react.png" alt="React"/></code>
<code><img height="32" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/mysql/mysql.png" alt="MySQL"/></code>
<code><img height="32" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/postgresql/postgresql.png" alt="PostegreSQL"/></code>
<code><img height="32" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/mongodb/mongodb.png" alt="MongoDB"/></code>
<code><img height="32" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/redis/redis.png" alt="Redis"/></code>


<!--
**lucascb/lucascb** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
