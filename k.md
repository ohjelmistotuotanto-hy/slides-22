% Ohjelmistotuotanto
% Matti Luukkainen ja ohjaajat Kalle Ilves, Petri Suhonen, Oskari Nuottonen, Tuukka Puonti
% syksy 2022

# Vesiputousmalli

![](https://raw.githubusercontent.com/mluukkai/ohjelmistotekniikka-kevat2019/master/web/images/l-1.png){ width=440 }

# luento 1

# Iteratiivinen ohjelmistokehitys

![](../ohjelmistotuotanto-hy.github.io/images/1-4.png){ width=400 }

# luento 2

# Scrum

![](../ohjelmistotuotanto-hy.github.io/images/2-1.png){ width=440 }

# luento 3

# Vaatimusmäärittely 2010-luvulla: Lean startup

![](../ohjelmistotuotanto-hy.github.io/images/2-3.png){ width=200 }

# User story

- Mike Cohn:

  - _A user story describes functionality that will be valuable to either user or purchaser of software._

- User stories are composed of three aspects:
  1. A written description of the story, used for planning and reminder
  2. Conversations about the story to serve to flesh the details of the story
  3. Tests that convey and document details and that will be used to determine that the story is complete

# luento 4

#

![](../ohjelmistotuotanto-hy.github.io/images/2-9.png){ width=350 }

# WIP-rajoitteet

![](./images/2-25b.png){ width=300 }

#

![](../ohjelmistotuotanto-hy.github.io/images/2-23.jpg){ width=450 }

# luento 5

#

- _Yksikkötestaus_ (unit testing)
- _Integraatiotestaus_ (integration testing)
- _Järjestelmätestaus_ (system testing)
- _Käyttäjän hyväksymistestaus_ (user acceptance testing)

![](../ohjelmistotuotanto-hy.github.io/images/3-3.png){ width=300 }

# Ohtuvarasto: tyhjä, puolitäysi, täysi

```python
class Varasto
    def __init__(self, tilavuus, alku_saldo = 0):
        self.tilavuus = tilavuus
        self.saldo = alkusalto

    def ota_varastosta(self, maara):
        if maara < 0:
            return 0.0

        if maara > self.saldo:
            kaikki_mita_voidaan = self.saldo
            self.saldo = 0.0
            return kaikki_mita_voidaan

        self.saldo = self.saldo - maara
        return maara
```
