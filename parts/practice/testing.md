---
id: d2b82094-dab5-4ade-8a42-138e872e1a60
title: Prüfen
authors:
  - tollwerk GmbH
---

{#zvzisrlz}

Bevor ein E-Book erscheint, wird es geprüft: automatisch mit EPUBCheck und Ace by DAISY :cite{ref=bibliography.yaml#daisy-2024}, und von Menschen, die assistive Technologien nutzen.

:::code[Prüfung mit EPUBCheck auf der Kommandozeile]{#hfqutepy}

```sh
java -jar epubcheck.jar demo-book.epub
```

:::

:::example[Ein Prüfprotokoll]{#ekajohxt}

Das Protokoll nennt für jeden Fund die Datei und die Zeile, etwa „chapter-structure.xhtml, Zeile 12: Überschriftenebene übersprungen“.

:::

:::question[Übung: Reihenfolge der Prüfung]{#l169qlup interaction=ordering}

Bringe die Schritte der Prüfung in eine sinnvolle Reihenfolge.

1. EPUBCheck ausführen {#s85si18b}
2. Ace by DAISY ausführen {#09jb3i3m}
3. Mit einem Screenreader lesen {#cny340cd}

---

Erst sichern die Werkzeuge, dass das E-Book technisch gültig ist, dann prüfen Menschen, ob es sich gut lesen lässt.

:::

:::question[Übung: Werkzeuge]{#p86sn938 interaction=text-entry}

Die Barrierefreiheit eines E-Books prüft das Werkzeug :gap[Ace]{#mpzr5161} by DAISY.

:::

:::reflection[Reflexion]{#p4w8j9ou feedback=hint}

Welche Lesesysteme nutzen die Menschen, für die du E-Books machst?

---

Denke auch an Lesegeräte mit E-Ink, Apps auf dem Smartphone und Vorlesefunktionen.

:::
