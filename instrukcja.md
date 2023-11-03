# Lekcja 1 – Markdown lekki język znaczników

## Wstęp
Obecnie powszechnie wykorzystuje się języki ze znacznikami do opisania dodatkowych informacji umieszczanych w plikach tekstowych. Z pośród najbardziej popularnych można wspomnieć o:
1.	html – służącym do opisu struktury informacji zawartych na stronach internetowych,

2.	Tex (Latex) – poznany na zajęciach język do „profesjonalnego” składania tekstów,

3.	XML (Extensible Markup Language) - uniwersalnym języku znaczników przeznaczonym do reprezentowania różnych danych w ustrukturalizowany sposób.

Przykład kodu html i jego interpretacja w przeglądarce:

```html
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8" />
<title>Przykład</title>
</head>
<body>
<p> Jakiś paragraf tekstu</p>
</body>
</html>
```
![Przykład kodu html na stronie internetowej](html.jpg)

Przykład kodu Latex i wygenerowanego pliku w formacie pdf
```Latex
\documentclass[]{letter}
\usepackage{lipsum}
\usepackage{polyglossia}
\setmainlanguage{polish}
\begin{document}
\begin{letter}{Szanowny Panie XY}
\address{Adres do korespondencji}
\opening{}
\lipsum[2]
\signature{Nadawca}
\closing{Pozdrawiam}
\end{letter}
\end{document}
```
![Wygenerowany plik pdf - Latex](Latex.jpg)

