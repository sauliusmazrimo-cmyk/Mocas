MOTO TRIP LOG - PWA

Kas viduje:
- index.html - pagrindinė programėlė
- manifest.json - PWA nustatymai
- sw.js - offline/cache service worker
- icon.svg - programėlės ikona

Kaip paleisti:
1. Įkelk visą aplanką į Netlify, GitHub Pages arba bet kurį HTTPS serverį.
2. Telefone atsidaryk nuorodą per Chrome.
3. Leisk naudoti vietą/GPS.
4. Chrome meniu pasirink „Add to Home screen“ arba naudok programėlės mygtuką „Įdiegti telefone“, jeigu naršyklė jį parodo.

Svarbu:
- GPS patikimai veiks tik per HTTPS arba localhost.
- Žemėlapio plytelėms paprastai reikia interneto.
- Duomenys saugomi telefono naršyklės localStorage. Prieš valydamas naršyklės istoriją eksportuok JSON.
- Fono GPS sekimas čia nedarytas sąmoningai. Tam vėliau reikia Android/native sprendimo.
