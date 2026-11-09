# Landing page – Ultimele 8 locuințe, Lebada Lake Residence

## Conținut
- `index.html` – pagina completă, cu CSS și JavaScript incluse, fără dependențe. Fonturile se încarcă de pe Google Fonts.
- `planuri/` – planurile celor 8 unități, decupate din relevee (`A4-6.jpg` … `A5-405.jpg`). Folderul trebuie să stea lângă `index.html`.

## Publicare
Pagina e servită de GitHub Pages din ramura `main`, la adresa din fișierul `CNAME` (oferta.lebadaresidence.ro). Orice modificare urcată pe `main` apare pe site în 1–2 minute.

## De completat în `index.html`
Căutați blocul `DE COMPLETAT LA PUNEREA PE SITE` din script:
- **STOC**: când se rezervă sau se vinde o unitate, schimbați `"disponibil"` în `"rezervat"` sau `"vandut"`. Contorul de stoc și cardurile se actualizează singure.
- **FORM_ENDPOINT**: adresa la care site-ul primește cererile de vizionare. Formularul trimite un POST cu JSON cu câmpurile `nume`, `telefon`, `email`, `unitate`, `data`, `interval`, `mesaj` și `primita`. Cât timp câmpul e gol, pagina afișează doar panoul „Sună-ne” cu 0721 230 742.

## De știut
- Prețurile sunt în euro, fără TVA. Prețul cu TVA 21% e calculat pe fiecare card.
- Perioada ofertei e 11.11.2026 – 18.12.2026, iar contorul de zile se calculează automat.
- Pentru Facebook se poate adăuga în `<head>` o imagine de previzualizare (`og:image`).

- Versiunea în engleză („The Last 8 Jewels”) e în `en/index.html`, la https://oferta.lebadaresidence.ro/en/. Dacă schimbi ceva în `index.html`, actualizează și varianta în engleză.
