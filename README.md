# Čarobna šuma — sajt

Statički sajt privatne predškolske ustanove „Čarobna šuma". Dve stranice, potpuno samostalne (sve — fontovi, slike, logika — ugrađeno u fajlove), rade offline i od ivice do ivice.

## Fajlovi
- `index.html` — glavna stranica (hero, o nama, grupe, jelovnik, projekti, galerija, kontakt, footer)
- `grupa.html` — stranica grupe; otvara se sa `grupa.html?g=jaslice` (vrednosti: `jaslice`, `mladja`, `starija`, `predskolsko`)

## Objava na GitHub Pages
1. Napravi novi repozitorijum na GitHub-u i otpremi ova dva fajla (+ ovaj README).
2. U repozitorijumu: **Settings → Pages**.
3. Pod „Build and deployment" izaberi **Deploy from a branch**, granu `main` i folder `/root`, pa **Save**.
4. Za par minuta sajt je dostupan na `https://<korisnicko-ime>.github.io/<repo>/`.

## Fotografije
Sve fotografije se nalaze u folderu `images/` (WebP format), imenovane po mestu na sajtu:
- `logo-brand.webp`, `logo-footer.webp` — logo (navigacija i footer)
- `hero-img.webp` — hero fotografija, `about-img.webp` — o nama
- `staff-1..4.webp` — vaspitači
- `gal-0..7.webp` — galerija
- `proj-1..3.webp` — projekti
- `grupa-hero-*.webp`, `grupa-vaspitac-*.webp` — stranice grupa

Iste slike su i ugrađene direktno u `index.html` i `grupa.html`, tako da sajt radi i bez foldera. Folder `images/` ti služi ako želiš da ih koristiš zasebno ili zameniš.

