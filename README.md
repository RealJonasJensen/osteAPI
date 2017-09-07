# OsteAPI Dokumentation

##Resurser 

### GET /cheeses

Resursen repræsenterer alle oste i kartoteket.
Resursen er formateret på følgende måde:

```JSON

[{"varenr": 8393,
    "navn": "Cornish Blue",
    "pris": 60,
    "type": "bluecheese",
    "producent": "Upton Cross.",
    "antal": 22,
    "beskrivelse":{
        "tekst": "Denne ost er cremede, mild og sød",
        "smag": "mild",
        "vægt": 500,
        "billede": "cornishbluecheese.jpg"
    }}]

```

### GET /cheeses/\<varenummer>

Resursen ræpresenterer en enkelt ost i kartoteket.
Resursen er formaterer på følgende måde:

````JSON

{
    "varenr": 15,
    "navn": "Grøn Alpheost",
    "pris": 24.99,
    "type": "Smøreost",
    "producent": "Arla",
    "antal": "875",
    "beskrivelse": {
        "tekst": "Lavet fra en ko, klar til at smøre",
        "smag": "mild",
        "vægt": 250,
        "billede": "alpeost-iv.jpg"
    }

```