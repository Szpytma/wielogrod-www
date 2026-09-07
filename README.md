# wielogrod.pl

Strona serwera Minecraft **Wielogród**. Hostowana na GitHub Pages, domena w OVH.

Nie edytuj plików tutaj. **Źródłem jest katalog `www/` w prywatnym repo `mcserver`**,
skąd trafiają tu skryptem `scripts/www-deploy.ps1`. Zmiana wprowadzona bezpośrednio
w tym repo zostanie nadpisana przy kolejnym wdrożeniu.

| Plik | Do czego |
|---|---|
| `index.html` | cała strona, jeden plik, bez zależności zewnętrznych |
| `logo.png`, `ikona.png` | znak serwera (`docs/brand/` w repo źródłowym) |
| `CNAME` | domena dla GitHub Pages — **nie usuwać** |
| `.nojekyll` | wyłącza przetwarzanie Jekyllem, strona jest statyczna |
