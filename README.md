```python3
from dataclasses import dataclass

# hey there, friends!

@dataclass
class Bioengineer:
    name: str
    bio: str
    code: list
    contact: dict

nb = Bioengineer(
    name = 'Nicolas',
    bio = 'Ph.D. student, Synthetic Biology + Machine Learning',
    code = ['Python', 'Rust', 'GO', 'TS/JS', 'C/C++'],
    contact = {
        'Homepage': 'nsbuitrago.xyz',
        'BlueSky': '@nsbuitrago.xyz',
        'Mail': 'nsb5 [at] rice [dot] edu'
    }
)
```
