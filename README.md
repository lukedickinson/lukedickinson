### Hey there 👋

<!--
**lukedickinson/lukedickinson** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
- 🔭 I’m currently working on my Certificate III in Information Digital Media and Technology
- 🌱 I’m currently aiming to gain entry to a Bachelor Degree, and become a Software Developer full time for an established company
- 👯 I’m looking to collaborate on any intermediate level projects in Python, C# and Java
- 📫 How to reach me: lukerobertdickinson@gmail.com
<br />
<h3>
    
```python
​
import json
from dataclasses import asdict, dataclass


@dataclass
class Stack:
    languages   : tuple = ("Python", "C#", "Java", "PHP")
    databases   : tuple = ("mySQL", "SQL Server")
    ongoing     : tuple = ("ASP.NET", "AWS")

    def serialize(self):
        return json.dumps(asdict(self), indent=4)


stack = Stack()
print(stack.serialize())
​
```
</h3>

![Luke's GitHub stats](https://github-readme-stats.vercel.app/api?username=lukedickinson&count_private=true&show_icons=true&theme=prussian)
