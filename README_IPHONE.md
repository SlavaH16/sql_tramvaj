# SQL Tramvaj – iPhone (PWA)

## Jak dostat aplikaci na iPhone
1. Publikuj všechny soubory z této složky do samostatného GitHub repozitáře (např. `sql-tramvaj`).
2. Na GitHubu otevři **Settings → Pages** a zapni nasazení z větve `main`, složka `/ (root)`.
3. Počkej na publikování a otevři zveřejněnou `https://...github.io/...` adresu v **Safari na iPhonu**.
4. V Safari klepni na tlačítko **Sdílet**.
5. Vyber **Přidat na plochu**. Pokud se zobrazí volba **Otevřít jako webovou aplikaci**, zapni ji.
6. Klepni na **Přidat**. Na ploše se objeví ikona SQL Tramvaj.

Aplikace je PWA: má ikonu, samostatné okno a základní offline cache po prvním načtení. Pokrok se ukládá v lokálním úložišti daného prohlížeče/instalace.

## Důležité
- Na iPhonu je potřeba stránku nejprve zveřejnit přes HTTPS; lokální HTML soubor sám o sobě se nedá spolehlivě nainstalovat jako webová aplikace.
- Tato verze sama neposílá oznámení v 7:00. iOS omezuje webová oznámení; lze je doplnit po publikování a povolení notifikací, nebo použít připomínku v aplikaci Připomínky.
