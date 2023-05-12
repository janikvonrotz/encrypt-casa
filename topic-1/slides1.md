# Slides Thema 1
## Sicherheitsprobleme

... und wie man diese behebt.

🎯 Sie verstehen die Sicherheitsziele des Nachrichtenaustausches.

---

### Nachrichtenaustausch

(A)lice schickt eine Nachricht an (B)ob.

![](./alice-to-bob.png)
(E)ve versucht die Nachricht abzuhören und zu verändern.

![](./alice-eve-bob.png)

🧠 Nice to know: Der Name Eve kommt von [Eavesdropping](https://en.wikipedia.org/wiki/Eavesdropping).

---

### Sicherheitsprobleme beim Austausch

* **Eve** sollte die Nachricht nicht mitlesen können (Vertraulichkeit)
* **Eve** sollte die Nachricht nicht verändern können (Integriät)
* **Bob** sollte sicher sein, dass Nachricht von **Alice** stimmt (Authentizität)
* **Alice** sollte nicht abstreiten könne, dass die Nachricht von ihr ist (Verbindlichkeit)

---

### Sicherheitsziele

Daraus leiten sich diese Ziele ab:

* **Vertraulichkeit** 😈: Die Nachricht, die man erhält, ist nicht von Unbefugten gelesen worden.
* **Integrität** 💎: Die Nachricht, die man erhält, ist nicht manipuliert worden.

---

* **Authentizität** 🙋‍: Die Nachricht, die man erhält, stammt wirklich von der Person, die als Absender angegeben ist.
* **Verbindlichkeit** 📝: Der Urheber kann nachträglich nicht bestreiten, die Nachricht verfasst zu haben.

---

### Aufgaben

🎬 Lösen Sie die [Aufgaben](excercise1.md#Aufgaben) 1 in Gruppen oder Breakout-Rooms.

---

### Massnahmen im Alltag

Im Alltag wenden wir das bereits an.

* Nachricht mit Signal ist End-2-End-verschlüsselt (Vertraulichkeit)
* Nachricht in Umschlag stecken (Integrität)
* Unterschrift auf Dokument (Authentizität, Verbindlichkeit)

🤔 Kennt ihr noch weitere Beispiele für die Sicherheitsziele?

---

### Massnahmen im Unternehmen

Dieselben Sicherheitsziele lassen sich für Rechnernetze realisieren.

* Moderne Verschlüsselung (Vertraulichkeit)
* Digitale Signatur (Integrität, Authentitzität, Verbindlichkeit)
