### Hey there š

<!--
**lukedickinson/lukedickinson** is a āØ _special_ āØ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- š­ Iām currently working on ...
- š± Iām currently learning ...
- šÆ Iām looking to collaborate on ...
- š¤ Iām looking for help with ...
- š¬ Ask me about ...
- š« How to reach me: ...
- š Pronouns: ...
- ā” Fun fact: ...
-->
- š­ Iām currently working on my Certificate III in Information Digital Media and Technology
- š± Iām currently aiming to gain entry to a Bachelor Degree, and become a Software Developer full time for an established company
- šÆ Iām looking to collaborate on any intermediate level projects in Python, C# and Java
- š« How to reach me: lukerobertdickinson@gmail.com
<br />
<h3>
    
```python
ā
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
ā
```
</h3>

![Luke's GitHub stats](https://github-readme-stats.vercel.app/api?username=lukedickinson&count_private=true&show_icons=true&theme=prussian)
