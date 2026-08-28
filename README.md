# Art Dental & Medical Solutions — GitHub Pages

Site static pregătit pentru publicare pe GitHub Pages.

## Înainte de publicare

1. Înlocuiește imaginile-placeholder din `assets/` cu imaginile reale, păstrând exact numele:
   - `dr-iacob.jpg`
   - `dr-mertic.jpg`
   - `harvard-cert.jpg`
2. Deschide `assets/site-config.js` și, dacă le ai, completează:
   - `clinicEmail` — pentru ca formularul să deschidă un email deja adresat clinicii;
   - `clinicAddress` — pentru afișarea adresei reale.

Dacă `clinicEmail` rămâne gol, formularul nu trimite date către un server: pregătește/copieză cererea și afișează numerele de telefon.

## Publicare pe GitHub Pages

1. Creează un repository nou pe GitHub.
2. Încarcă **conținutul acestui folder** în rădăcina repository-ului (`index.html`, `assets/`, `.nojekyll`).
3. În GitHub intră la **Settings → Pages**.
4. La **Build and deployment**, alege **Deploy from a branch**.
5. Selectează branch-ul `main` și folderul `/ (root)`, apoi **Save**.
6. GitHub va afișa linkul public al site-ului în aceeași pagină.

## Observații

- Site-ul este responsive pentru telefon/tabletă/desktop.
- Meniul mobil este funcțional.
- Lista de prețuri și căutarea sunt JavaScript local, fără backend.
- Formularul este compatibil cu hosting static; pentru trimitere automată fără client email este nevoie ulterior de un serviciu de formulare sau de un backend.
