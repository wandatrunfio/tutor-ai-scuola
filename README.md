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
| `docente.html` | Parte 5 – Assistente del docente per lezioni, UDA e verifiche |

Ogni tutor ha: nome, descrizione, istruzioni complete da copiare (sotto gli 8.000 caratteri), prompt iniziali, fonti di conoscenza consigliate, argomenti per Copilot Studio e idee per la classe.

## Pubblicare su GitHub Pages

1. Crea un nuovo repository su GitHub (es. `tutor-ai-scuola`), pubblico.
2. Carica nella radice del repository i 6 file `.html` e `README.md` (ogni pagina contiene già il proprio stile: non servono altre cartelle).
   - Dal sito: **Add file → Upload files**, trascina i file, poi **Commit changes**.
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

Le pagine sono HTML semplice: si possono modificare direttamente con qualsiasi editor (anche dal sito di GitHub con l'icona della matita). Lo stile e il pulsante "Copia" sono inclusi in ogni pagina (tag `<style>` e `<script>`).

## Avvertenze

- Le interfacce di Microsoft 365 Copilot e Copilot Studio cambiano spesso: i nomi dei pulsanti possono variare.
- Prima dell'uso con gli studenti verificare con Dirigente e DPO: account istituzionali, informativa privacy, consenso dei genitori per i minori di 14 anni (Legge 132/2025, art. 4).
- Questo progetto non è affiliato a Microsoft.

## Licenza

A cura di **Wanda Trunfio** – formatrice AI · Contatti: [wanda.trunfio.formazione@gmail.com](mailto:wanda.trunfio.formazione@gmail.com)

Contenuti rilasciati con licenza [Creative Commons Attribuzione – Non commerciale – Condividi allo stesso modo 4.0 Internazionale (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.it): puoi riutilizzarli e modificarli citando l'autrice, non a fini commerciali e condividendo le opere derivate con la stessa licenza.

## Trasparenza metodologica sull'impiego dell'IA

L'intelligenza artificiale generativa è stata utilizzata come strumento di supporto alla ricerca, all'organizzazione dei contenuti e alla produzione dei materiali.
L'architettura del lavoro, la selezione delle fonti, la revisione, la verifica e la validazione dei contenuti sono state curate dall'autrice secondo un approccio Human-in-the-Loop, che mantiene il controllo editoriale e assume la responsabilità scientifica e didattica dei materiali pubblicati.
