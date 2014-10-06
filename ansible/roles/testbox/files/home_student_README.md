# Test Linux

Een paar tips/instructies voor het gebruik van deze VM

## Instructies

- Gebruik van het _Internet_ is niet toegelaten
- Hou de VM altijd in _full screen_ ([RCtrl]+F)
- Schakel na afloop van de test de VM _volledig uit_, maar laat de pc aan staan.

## Tips

- De gebruiker student heeft _sudo_-rechten
- Open verschillende _terminals_ met [RCtrl]+[F1] t/m [F6]
- De _muis_ werkt binnen de VM. Geselecteerde tekst is ook meteen gekopieerd, plakken doe je met middelste of rechter muisklik
- Verander de toetsenbord-layout met het commando `sudo loadkeys`, bv. `sudo loadkeys us` of `sudo loadkeys us-colemak`

## Geïnstalleerde packages

Deze VM is een minimale installatie met volgende toegevoegde packages:

- apg (password generator)
- bind-utils (nslookup)
- bzip2
- gpm (muisondersteuning in terminal)
- man-pages
- nano (Teksteditor, met syntaxcoloring)
- psmisc (commando pstree)
- tree
- vim-enhanced (je favoriete teksteditor ;-)
- words (woordenlijst)
- zip
