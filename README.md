# Max/MSP Knowledge

Hier ein paar nützliche Links und Tipps zum Thema **Max/MSP**

## Überblick

Max ist eine visuelle Programmiersprache und Laufzeitumgebung für Multimediaanwendungen, die sich in der Version **8**
[hier](https://cycling74.com/downloads)
herunterladen lässt.

In der [Ausleihe](https://shoptechnikfbmd.iqrent.de/search/?keyword=MAX7) lassen sich Lizenzen/Dongles für Max ausleihen.
Dort gibt es bisher nur Dongles für **Max 7**. Das steht [hier](https://cycling74.com/downloads/older) zum Download bereit.
Damit die Aktivierung mit einem Dongle funktioniert muss der [Pace License Manager](https://www.paceap.com/pace-management.html) installiert sein.

Wer keine Lust hat auf die Ausleihe angewiesen zu sein, kann [hier](https://cycling74.com/shop) eine eigene Lizenz erwerben. Nach einer Registrierung auf der Seite von Cycling'74 kann man sich dort als Student*in verifiziern lassen und hat dann Anspruch auf eine vergünstige *Academic Licence*.

## Einstieg

### Documentation in Max finden

Fast alle Tutorials in diesem Abschnitt finden sich auch direkt innerhalb von Max.
Um dorthin zu kommen sind folgende Schritte notwending:

```
File -> Filebrowser (oder CMD+B auf MacOS bzw CTRL + B auf Win)

In der linken Seitenleiste -> Cycling'74 Content (siehe Bild)

```

![](https://github.com/jonasohland/h_da-smp-max-knowledge/raw/master/find_tutorials_filebrowser.png) <!--- { width=250px } -->

### Object Help

Abseits davon lohnt es sich immer, mal einen Blick auf die Helppage von einzelnen Max-Objekten zu werfen. Dazu reicht ein Rechtsklick auf das Objekt gefolgt von einem gezielten Linksklick auf `show [OBJ] help`.

## Online Documentation

Alles was wirklich über Max wissen muss findet sich in der Max Documentation:

[Max Documentation](https://docs.cycling74.com/max7/)

Die Grundlagen von Max (Objects, Syntax, Messages, Datatypes). Es lohnt sich hier anzufangen um die Grundlagen zu verstehen:

[Basic Max Tutorials](https://docs.cycling74.com/max7/tutorials/00_maxindex)

Je nach Kenntnisstand von Themen rund um das Thema DSP und Digital Audio empfiehlt sich die folgende Einführung in das Thema:

[How Digital Audio Works](https://docs.cycling74.com/max7/tutorials/02_mspdigitalaudio)

Danach ist es Zeit sich endlich in die Welt von Signalen, Oszillatoren und Filtern zu stürzen:

[Max MSP (Max Signal Processing) Tutorials](https://docs.cycling74.com/max7/tutorials/00_mspindex)

Und wem das an dieser Stelle noch nicht reicht, der kann sich mit **Gen** beschäftigen:

[Max Gen Tutorials](https://docs.cycling74.com/max7/vignettes/gen_topic)

Wer es bis hier geschafft hat ist inzwischen Max-Experte und bereit für die Reference! Hier finden sich ausführliche Informationen über jedes einzelne Objekt und jede einzelne Methode und Message im ganzen Max-Universum:

[Max Object Reference](https://docs.cycling74.com/max7/vignettes/docrefpages)

Und weil Vergessen menschlich ist, gibt es hier das Max Cheetsheet. Darauf sind die Basics nochmal in Kurzform zusammengefasst. Empfiehlt sich für Wieder- und Quereinsteiger:

[Max Cheetsheet](https://cycling74-web-uploads.s3.amazonaws.com/5462c2a9bdbb99652da7a00a/2017-05-11T08:53:04Z/cheatsheet.pdf)

## Fortgeschrittenes

### Cycling'74 Forum

Im [Forum](https://cycling74.com/forums/page/1) findet man eine Antwort auf so ziemlich alles. Die Community ist sehr beginnerfreundlich und meistens antwortet nach kurzer Zeit einer der dort sehr aktiven Max-Entwickler. Allerdings gilt auch hier die goldene Regel jeder Help-Community: **erst Suchen, dann Fragen**.

### Videos, Tutorials, etc.
[Delicious Max Tutorials](https://www.youtube.com/playlist?list=PLD45EDA6F67827497) ist eine sehr empfehlenswerte Tutorial-Serie von *Sam Tarakajian* einem der Entwickler von Max bei Cycling'74.

[Max Community Tutorials](https://cycling74.com/tutorials/page/1). Hier findet man zahlreiche interessante Tutorials und Inspirationen die ein wenig über die Basics hinaus gehen.

[Javascript in Max](https://docs.cycling74.com/max7/vignettes/javascriptinmax) Hier gibt es zusätzliche Informationen über Javascript in Max. Diese gehen nochmal deutlich über das hinaus was man in der Dokumentation von `js` findet.


## Externals

Eigentlich gibt es in Max ein Objekt für so ziemlich alles. Und sollte mal eins nicht geben, dann gibt es mit Sicherheit ein External dafür.
Externals sind zusätzliche Objekte, die sich überall im Internet verstreut finden.

### Externals installieren

Externals sind Dateien die unter MacOS die Endung `.mxo` und unter Windows die Endung `.mxe64` aufweisen.
Externals unter Windows mit der Endung `.mxe` benötigen eine 32-bit Version von Max.

Wenn nicht anders beschrieben sollten Externals installiert werden in:

Windows
```
C:\Users\YourNameHere\Documents\Max 8\Library\
```

MacOS
```
/Users/jonasohland/Documents/Max 8/Library/
```

Viele Externals lassen sich auch einfach über den Max Package Manager installieren. Dieser findet sich in Max unter:
```
File -> Show Package Manager
```

### Nützliche Externals für den Alltag

**Ambisonics**

Essentielle Externals für Ambisonics (Encoder Decoder and more):
[ICST Externals](https://www.zhdk.ch/forschung/icst/software-downloads-5379/downloads-ambisonics-externals-for-maxmsp-5381) (Verfügbar im Package Manager)

Alternative inklusive Binaural Decoder:
[HOA Library](https://github.com/CICM/HoaLibrary-Max/releases)

**OSC**

OSC und noch viel mehr:
[odot Externals](https://github.com/CNMAT/CNMAT-odot/releases)

Alternative OSC Externals aus dem gleichen Haus:
[CNMAT Externals](https://github.com/CNMAT/CNMAT-Externs/releases) (Verfügbar im Package Manager)

**Machine Learning**

Machine Learning in Max/MSP mit vielen interessanten Beispielen:
[ml.star](https://cycling74.com/articles/content-you-need-ml%C2%B7star) (Verfügbar im Package Manager)

**Computer Vision**

CV Externals für jitter:
[cv.jit](https://jmpelletier.com/cvjit/) (Verfügbar im Package Manager)



## Ergänzugen

Wenn hier etwas fehlt oder ihr noch etwas spannendes im Internet gefunden habt, dann schreibt mir einfach eine [Mail](mailto:jonas.ohland@stud.h-da.de) oder eröffnet [hier](https://github.com/jonasohland/h_da-smp-max-knowledge) eine Issue.
