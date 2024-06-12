```python
from typing import Tuple, List, Dict

class Nitrix:
    pass

class Attributes(Nitrix):
    @property
    def contact(self) -> Tuple[Tuple[str], Tuple[str]]:
        telegram = ("t.me/nitrixv3",)
        discord = ("voltuxcloud",)
        return telegram, discord

    @property
    def life(self) -> Tuple[List[str], int]:
        langs = ['English']
        age = 15
        return langs, age
    
    @property
    def coding(self) -> Tuple[Dict[str, List[str]], List[str], List[str], Dict[str, Dict[str, Dict[str, str]]]]:
        langs = {
            'expert': ['c', 'python'],
            'intermediate': ['c++', 'js'],
            'learning': ['go', 'java']
        }
        specialities = ['networking', 'fullstack']
        ide = ['vscode']
        pc = {
            'Windows Desktop': {
                'Custom': {
                    'processor': 'i7-11700K',
                    'ram': '16GB',
                    'gpu': 'RTX 2070'
                }
            }
        }
        return langs, specialities, ide, pc
```
