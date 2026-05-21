# Internationals

A mirror of the [40000+ International (men's) football match results from 1872 to 2026](https://github.com/martj42/international_results)
dataset by Mart Jürisoo
using the Football.TXT format and split by tournament (major "top-level"/more)
and year e.g.


```
├───afc_asian_cup
│       1956_afc_asian_cup.txt
│       1960_afc_asian_cup.txt
│       1964_afc_asian_cup.txt
│       1968_afc_asian_cup.txt
│       1972_afc_asian_cup.txt
│       1976_afc_asian_cup.txt
│       1980_afc_asian_cup.txt
│       1984_afc_asian_cup.txt
│       1988_afc_asian_cup.txt
│       1992_afc_asian_cup.txt
│       1996_afc_asian_cup.txt
│       2000_afc_asian_cup.txt
│       2004_afc_asian_cup.txt
│       2007_afc_asian_cup.txt
│       2011_afc_asian_cup.txt
│       2015_afc_asian_cup.txt
│       2019_afc_asian_cup.txt
│       2024_afc_asian_cup.txt
...
└───uefa_nations_league
        2018_uefa_nations_league.txt
        2019_uefa_nations_league.txt
        2020_uefa_nations_league.txt
        2021_uefa_nations_league.txt
        2022_uefa_nations_league.txt
        2023_uefa_nations_league.txt
        2024_uefa_nations_league.txt
        2025_uefa_nations_league.txt
```

Note - the [/more](more) directory incl. 180+ more tournaments, only the "major"
tournaments (& qualifications) are listed on top-level.


See (DIRECTORY/FILE) [TREE.md »](TREE.md)



For a list of all 330+ teams by year (with tournaments and match counts),
see [TEAMS.md »](TEAMS.md)

For example, the entry for England reads:

**England** <br>
1872 to 2026  - 146 years <br>
<details><summary>1091 match(es) in 11 tournament(s)</summary>

- Friendly (111 years/429 matches) 1872 1873 1874 ... 2024 2025 2026
- British Home Championship (91/263) 1884 1885 1886 ... 1982 1983 1984
- FIFA World Cup qualification (32/127) 1949 1950 1956 ... 2017 2021 2025
- FIFA World Cup (17/77) 1950 1954 1958 ... 2018 2022 2026
- UEFA Euro qualification (28/110) 1962 1963 1968 ... 2015 2019 2023
- UEFA Euro (11/45) 1968 1980 1988 1992 1996 2000 2004 2012 2016 2021 2024
- Rous Cup (5/8) 1985 1986 1987 1988 1989
- USA Cup (1/3) 1993
- Tournoi de France (1/3) 1997
- King Hassan II Tournament (1/2) 1998
- UEFA Nations League (5/24) 2018 2019 2020 2022 2024

</details>

and for Austria:

**Austria** <br>
1902 to 2026  - 119 years <br>
<details><summary>862 match(es) in 10 tournament(s)</summary>

- Friendly (116 years/475 matches) 1902 1903 1904 ... 2023 2024 2026
- Olympic Games (1/5) 1912
- Central European International Cup (16/48) 1927 1928 1929 ... 1956 1957 1958
- FIFA World Cup qualification (35/142) 1934 1937 1953 ... 2021 2022 2025
- FIFA World Cup (8/32) 1934 1954 1958 1978 1982 1990 1998 2026
- UEFA Euro qualification (29/118) 1959 1960 1963 ... 2015 2019 2023
- Tournoi de France (1/2) 1988
- Cyprus International Tournament (1/2) 2005
- UEFA Euro (4/14) 2008 2016 2021 2024
- UEFA Nations League (5/24) 2018 2020 2022 2024 2025

</details>



> The matches range from FIFA World Cup to FIFI Wild Cup to regular friendly matches.
> The matches are strictly men's full internationals and the data does not include
> Olympic Games or matches where at least one of the teams
> was the nation's B-team, U-23 or a league select team.

For a list of all tournaments a-z, see [TOURNAMENTS.md »](TOURNAMENTS.md)

and for a list of all tournaments by year, see [TOURNAMENTS_BY_YEAR.md »](TOURNAMENTS_BY_YEAR.md)




## Football.TXT Examples


[`gold_cup/2025_gold_cup.txt`](gold_cup/2025_gold_cup.txt)

```
= Gold Cup 2025

# Date       Sat Jun 14 - Sun Jul 6 2025 (22d)
# Teams      16
# Matches    31

Sat Jun 14
  Mexico                 3-2 Dominican Republic       @ Inglewood, United States
     (Edson Álvarez 44' Raúl Jiménez 47' César Montes 53';
      Peter González 51' Edison Azcona 67')
Sun Jun 15
  Costa Rica             4-3 Suriname                 @ San Diego, United States
     (Alonso Martínez 14' Manfred Ugalde 19'(p),90'(p) Josimar Alcócer 76';
      Gyrano Kerk 34' Richonell Margaret 59' Shaquille Pinas 64'(p))
  United States          5-0 Trinidad and Tobago      @ San Jose, United States
     (Malik Tillman 16',41' Patrick Agyemang 44' Brenden Aaronson 82' Haji Wright 84')
  Haiti                  0-1 Saudi Arabia             @ San Diego, United States
     (Saleh Al-Shehri 21'(p))

...

Wed Jul 2
  United States          2-1 Guatemala                @ St. Louis, United States
     (Diego Luna 4',15'; Olger Escobar 80')
  Mexico                 1-0 Honduras                 @ Santa Clara, United States
     (Raúl Jiménez 50')
Sun Jul 6
  United States          1-2 Mexico                   @ Houston, United States
     (Chris Richards 4'; Raúl Jiménez 27' Edson Álvarez 77')
```

or [`fifi_wild_cup/2006_fifi_wild_cup.txt`](more/fifi_wild_cup/2006_fifi_wild_cup.txt)

```
= FIFI Wild Cup 2006

# Date       Mon May 29 - Sat Jun 3 2006 (5d)
# Teams      6
# Matches    10

Mon May 29
  Northern Cyprus        1-0 Greenland                @ Hamburg, Germany
  Republic of St. Pauli  1-1 Gibraltar                @ Hamburg, Germany
Tue May 30
  Zanzibar               1-3 Northern Cyprus          @ Hamburg, Germany
  Republic of St. Pauli  7-0 Tibet                    @ Hamburg, Germany
Wed May 31
  Gibraltar              5-0 Tibet                    @ Hamburg, Germany
  Greenland              2-4 Zanzibar                 @ Hamburg, Germany
Thu Jun 1
  Northern Cyprus        2-0 Gibraltar                @ Hamburg, Germany
  Republic of St. Pauli  1-2 Zanzibar                 @ Hamburg, Germany
Sat Jun 3
  Republic of St. Pauli  1-2 Gibraltar                @ Hamburg, Germany
  Northern Cyprus        0-0 Zanzibar                 @ Hamburg, Germany   [Northern Cyprus wins on penalties]
```






## What's missing in the (upstream) match results?

- The match result (score) has no flag for after extra-time (aet) or after golden goal extra-time (agget) etc.
- No match status - e.g. match awarded, abandoned, annulled, withdrawn, etc.
- The penalty shootout result is binary only, that is, listing the winner BUT not the penalty shootout score.
- The goal scorer minutes do NOT track injury time e.g. `45'+2` or `90'+3` or such.




Bonus - Adding rounds (e.g. final/semi-final/quarter-final or such) is a work-in-progess upstream (and not included in the official public dataset).
Get / download the `stages.csv` used / added in this mirror,
from the issue ticket [Add structure/stage of tournaments #22](https://github.com/martj42/international_results/issues/22).



[`copa_america/2024_copa_america.txt`](copa_america/2024_copa_america.txt)

```
= Copa América 2024

# Date       Thu Jun 20 - Sun Jul 14 2024 (24d)
# Teams      16
# Matches    32


▪ Group A
Thu Jun 20
  Argentina              2-0 Canada                   @ Atlanta, United States
     (Julián Álvarez 49' Lautaro Martínez 88')
Fri Jun 21
  Peru                   0-0 Chile                    @ Arlington, United States

...

▪ Semi-final
Tue Jul 9
  Argentina              2-0 Canada                   @ East Rutherford, United States
     (Julián Álvarez 22' Lionel Messi 51')
Wed Jul 10
  Uruguay                0-1 Colombia                 @ Charlotte, United States
     (Jefferson Lerma 39')

▪ Third place playoff
Sat Jul 13
  Canada                 2-2 Uruguay                  @ Charlotte, United States   [Uruguay wins on penalties]
     (Ismaël Koné 22' Jonathan David 80';
      Rodrigo Bentancur 8' Luis Suárez 90')

▪ Final
Sun Jul 14
  Argentina              1-0 Colombia                 @ Miami Gardens, United States
     (Lautaro Martínez 112')

```






## Tips & Tricks


Tip - You can use the [`fbtxt2json` command-line tool](https://github.com/sportdb/footty/tree/master/fbtxt2json) to convert any file in the Football.TXT format to JSON.

Let's try to convert the FIFI Wild Cup 2006
in the Football.TXT format - see [`fifi_wild_cup/2006_fifi_wild_cup.txt`](more/fifi_wild_cup/2006_fifi_wild_cup.txt) - to JSON:

```
$ fbtxt2json fifi_wild_cup/2006_fifi-wild_cup.txt -o wild_cup.json
```
