% Ohjelmistotuotanto
% Matti Luukkainen ja ohjaajat Kalle Ilves, Petri Suhonen, Oskari Nuottonen, Tuukka Puonti
% syksy 2022

# Vesiputousmalli

![](https://raw.githubusercontent.com/mluukkai/ohjelmistotekniikka-kevat2019/master/web/images/l-1.png){ width=440 }

# Iteratiivinen ohjelmistokehitys

![](../ohjelmistotuotanto-hy.github.io/images/1-4.png){ width=400 }

# Scrum

![](../ohjelmistotuotanto-hy.github.io/images/2-1.png){ width=440 }

#

# Ohjelmistotekniikka

#

![](./images/todo1.png){ width=440 }

# Sekvenssikaavio

Mitä tapahtuu, kun maksukortilla jolla on rahaa 3 euroa, ostataan edullinen lounas?

```python
class Kassapaate:
    def __init__(self):
        self.EDULLISEN_HINTA = 2.5

    def syo_edullisesti(self, kortti: Maksukortti):
        if kortti.saldo < self.EDULLISEN_HINTA:
            return False

        kortti.ota_rahaa(self.EDULLISEN_HINTA):
        self.edulliset += 1
        return True
```
