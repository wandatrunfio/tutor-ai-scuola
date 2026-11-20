# Tutor AI a scuola

Sito statico con guide e modelli pronti per creare **Tutor AI** con **Microsoft Copilot Lite** (Agent Builder in Microsoft 365 Copilot) e **Copilot Studio**, per ogni disciplina della **scuola primaria** e della **secondaria di primo grado**.

## Contenuti

| Pagina | Contenuto |
|---|---|
| `index.html` | Presentazione, confronto Lite/Studio, regole d'oro, avvertenze |
| `guida-copilot-lite.html` | Parte 1 – Creare un tutor con Copilot Lite |
| `guida-copilot-studio.html` | Parte 2 – Creare un tutor con Copilot Studio completo |
| `primaria.html` | Parte 3 – 12 tutor disciplinari per la primaria |
| `secondaria.html` | Parte 4 – 14 tutor disciplinari per la secondaria di I grado |

Ogni tutor ha: nome, descrizione, istruzioni complete da copiare (sotto gli 8.000 caratteri), prompt iniziali, fonti di conoscenza consigliate, argomenti per Copilot Studio e idee per la classe.

## Pubblicare su GitHub Pages

1. Crea un nuovo repository su GitHub (es. `tutor-ai-scuola`), pubblico.
2. Carica tutti i file di questa cartella mantenendo la struttura (`index.html` nella radice, la cartella `assets/`).
   - Dal sito: **Add file → Upload files**, trascina i file e la cartella, poi **Commit changes**.
   - Da terminale:
     ```bash
     git init
     git add .
     git commit -m "Prima pubblicazione"
     git branch -M main
     git remote add origin https://github.com/TUO-UTENTE/tutor-ai-scuola.git
     git push -u origin main
     ```
3. Nel repository vai in **Settings → Pages**.
4. In **Build and deployment** scegli **Source: Deploy from a branch**, branch `main`, cartella `/ (root)`, poi **Save**.
5. Dopo un paio di minuti il sito è online su `https://TUO-UTENTE.github.io/tutor-ai-scuola/`.

Il file `.nojekyll` evita che GitHub elabori il sito con Jekyll.

## Modificare i contenuti

Le pagine sono HTML semplice: si possono modificare direttamente con qualsiasi editor (anche dal sito di GitHub con l'icona della matita). Lo stile è in `assets/style.css`, il pulsante "Copia" in `assets/app.js`.

## Avvertenze

- Le interfacce di Microsoft 365 Copilot e Copilot Studio cambiano spesso: i nomi dei pulsanti possono variare.
- Prima dell'uso con gli studenti verificare con Dirigente e DPO: account istituzionali, informativa privacy, consenso dei genitori per i minori di 14 anni (Legge 132/2025, art. 4).
- Questo progetto non è affiliato a Microsoft.

## Licenza

Contenuti rilasciati con licenza [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.it): puoi riutilizzarli e modificarli citando la fonte.
