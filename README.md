# **_Eviscerate.Persist.Intimidate-**
## E.P.I

To repozytorium zawiera projekt napisany w języku C# na silniku Unity Engine. Jego tematem jest implementacja gry typu Space Invaders (dwuwymiarowej strzelanki). 

**W repozytorium znajduje się plik EvisceratePersistIntimidate(x64).exe, który uruchomi aplikację; plik został stworzony przez Inno Setup Compiler**

## Opis

Eviscerate.Persist.Intimidate to zręcznościowa gra wideo wzorowana na retro klasyku - Space Invaders (Japoński:スペースインベーダー), który został stworzony przez Tomohiro Nishikado i wydany w 1978 roku. 

To jedna z najstarszych strzelanek, której celem jest pokonanie fal kosmitów działem laserowym, aby zdobyć jak najwięcej punktów.

![SpaceInvaders](https://upload.wikimedia.org/wikipedia/en/2/20/SpaceInvaders-Gameplay.gif)

## Rozgrywka

# Cel

Zadaniem gracza jest pokonanie pięciu rzędów jedenastu najeźdców (3 różych rodzajów). 

Fale kosmitów zbliżają się do dolnej części ekranu odbijając się poziomo od bocznych krawędzi mapy.

# Sterowanie

Gracz kieruje statkiem z działem laserowym, za pomocą strzałek, przesuwając je poziomo po dolnej części ekranu i strzelając do atakujących kosmitów. 

**Ruch w lewo - lewa strzałka; Ruch w prawo - prawa strzałka; Strzał - górna strzałka.**

# Punktacja

Gracz pokonuje kosmitów i zdobywa punkty za każdą sekunde przeyżtą na mapie. 

Im więcej kosmitów zostaje pokonanych tym szybciej się poruszają.

Punkty naliczane są od 0.

# Życia 

**Gracz ma 1 życie.**

Gracz traci życie w momencie:

- oberwania pociskiem
- zniszczenia statku przez fale kosmitów

Po każdej utracie życia gra i punkty ulegają resetowi.

# Finał

Gra kończy się w momencie:

- wyeliminowania wszystkich kosmitów
- strącenia statku matki

## Screeny 

**Menu Start**
![MenuStart](https://imgur.com/YHAuN1X)

**Gameplay**
![Gameplay](https://imgur.com/nFMR2Lw)

**Ending Screen**
![EndingScreen](https://imgur.com/JReyive)

## Źródła

[1] [Wikipedia - Space Invaders](https://en.wikipedia.org/wiki/Space_Invaders)

# Autorzy: Kosma Kierek / Michał Ogiba
# Silnik: Unity Engine
# Język: C#
# Hotel: Trivago