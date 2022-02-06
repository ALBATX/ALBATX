<h2> Hi, I'm Albat! <img src="https://media.giphy.com/media/mGcNjsfWAjY5AEZNw6/giphy.gif" width="50"></h2>
<img align='right' src="https://i.hizliresim.com/q8VJZx.png" width="230">
</br>Founder & CEO at <a href="https://partivo.net/">Partivo</a><img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30"> </em></p>


### <img src="https://media.giphy.com/media/l1J9w5fqmQ3qEBOdW/giphy.gif" width="50"> About me...  

<h3>
    
```python
​
import json
from dataclasses import asdict, dataclass


@dataclass
class Stack:
    code        : tuple = ("Javascript", "C#", "HTML", "CSS")
    databases   : tuple = ("PostgreSQL", "Mongo", "Redis")
    misc        : tuple = ("Visual Studio Code", "XenForo")
    ongoing     : tuple = ("C++", "PHP", "QT")

    def serialize(self):
        return json.dumps(asdict(self), indent=4)


stack = Stack()
print(stack.serialize())
​
```
</h3>

[![Spotify](https://novatorem-albatx.vercel.app/api/spotify)](https://open.spotify.com/user/j4ntqa7lm32ugu039446fdr96)


