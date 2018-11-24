# 4. Gebruikers en rechten

> :pushpin: Voorgaande oefeningen namen je bij de hand. Deze oefeningen geven minder weg. Soms moet je even iets opzoeken op internet. Het scheelt dat heel erg veel is gedocumenteerd online. Je kan ook elkaar helpen en mij om hulp vragen.

Gnu/Linux heeft een schitterend gebruikers- en rechten-systeem. Dat heb je ook in de presentatie van zojuist kunnen zien. We gaan dat nu in de praktijk zien, we gaan een aantal gebruikers en groepen aanmaken en de rechten goed zetten zodat iedereen recht heeft waar hij recht op zou moeten hebben.

maak de volgende mappen structuur aan in de map die je in de vorige oefening hebt aangemaakt op de desktop.

```bash
oefening4
 ├── junk
 ├── shared
 └── users
     ├── cognac
     └── quintor
```

De commando's die je nodig hebt (naast de commando's die we al hebben behandeld) zijn (voor sommige commando's heb je sudo-rechten nodig):

| commando                                 |  omschrijving                                                    | 
|------------------------------------------|:----------------------------------------------------------------:|
| `adduser <usernaam>`                     | Een nieuwe gebruiker toevoegen                                   |
| `groupadd <groepnaam>`              | Een nieuwe groep toevoegen                                            |
| `usermod -aG <group> <usernaam>`         | Een gebruiker aan een groep toevoegen                            |
| `su - <usernaam>`                        | switch user naar `<usernaam>`  (`exit` om terug te keren)        |
| `chown <usernaam>:<groep> <pad/bestand>` | verander de eigenaar van een pad of bestand                      |
| `chmod <modi> <pad>`                     | verander de bestands modi (schrijf-/lees-/uitvoer-rechten)       |
| `ls -al` of `ll`                         | Alternatief op `ls` om meer details te zien, zoals de rechten    |

- Maak twee nieuwe gebruikers aan cognac en quintor en geef ze dezelfde groep.
- Zorg dat ze beide kunnen schrijven in de map **Junk**
- Zorg dat ze beide kunnen lezen, maar niet schrijven in de map **share**
- Zorg dat de gebruikers zelf in hun map kunnen lezen én schrijven, maar niet kunnen lezen en schrijven in de map van een ander. 

Je kunt gebruik maken van een [chmod calculator](https://chmod-calculator.com/)

:thumbsup: Volgende hoofdstuk [Snap](../snap/) :fast_forward: