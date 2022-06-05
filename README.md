# Czech Deepspeech Model

This is an experimental deepspeech model for the Czech language. The model is under the CC-BY-NC license. Datasets used are:

- [Vystadial 2016 – Czech data](https://lindat.cz/repository/xmlui/handle/11234/1-1740) by Plátek, Ondřej ; Dušek, Ondřej ; Jurčíček, Filip (CC-BY-SA 4.0)
- [OVM – Otázky Václava Moravce](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-000D-EC98-3) by Šmídl, Luboš ; Pražák, Aleš (CC-BY-NC 3.0)
- [Czech Parliament Meetings](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0005-CF9C-4) by Pražák, Aleš ; Šmídl, Luboš (CC-BY-NC-ND 3.0)
- [Large Corpus of Czech Parliament Plenary Hearings](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-3126) by Kratochvíl, Jonáš ; Polák, Peter ; Bojar, Ondřej (CC-BY 4.0)
- [Common Voice Czech](https://commonvoice.mozilla.org/en/datasets) by Mozilla (CC0)
- Some private recordings and parts of audioboooks

The model has been originally transfer-learned from the [English Deepspeech/Coqui model](https://github.com/coqui-ai/STT/releases/tag/v0.9.3) version 0.9.3.

Released scorers have been created using the [CWC 2011 Corpus](https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0006-B847-6) by Spoustová, Johanka and Spousta, Miroslav (CC-BY 3.0) as well as [Wikipedia XML dump](https://dumps.wikimedia.org/backup-index.html), [Czech part of Europarl v7](https://www.statmt.org/europarl/), public domain [e-books from Municipal Library of Prague](https://www.mlp.cz/cz/katalog-on-line/eknihy/) and transcriptions of the training data.

