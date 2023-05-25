# Jak začít s react
- z internetu si potřebujeme stáhnout **npm** a **node.js**
- do prohlížeče stáhnoout rozšíření **react developer tools**

## Nastavení projektu
- vytvoříme si adresář, v jakém budeme projekt vyvíjet
- adresář pomocí **npm** nastavíme

### Práce s npm
- `npm -v` - zobrazí aktuální verzi naistalovaného npm
- `npm init` - inicializuje nový projekt a vytvoří **package.json**, který obsahuje metadata a závislosti pro daný projekt
- `npm i typescript -g` - nainstalije typescript
- `npm i react react-dom node` - nainstaluje **react**, **react-dom** (knihovna rozhraní mezi webovým prohlížečem a reactem) a **node.js**
- `npm i @types/react-dome` - nainstaluje typy pro react (rozšíří IDE o react balíček, automaticky pank např. dokončuje kód)
- `npm config set registry https://registry.npmjs.org/` - nastaví registrační URL, které NPM používá pro stahování balíčků
- `tsc --init` - inicializuje projekt s použitím TypeScriptu (konfigurace pro kompilaci a chování TypeScriptu)

### Konfigurace tsconfig.json
 - `// "jsx": "preserve",` **na** `"jsx": "react-native",` *(přípona .js + zůstává .jsx zápis)*
 - `// "outDir": "./",` **na** `"outDir": "dist",` *(uložení zkompilovaných souborů)*
 - `// "rootDir": "./",` **na** `"rootDir": "src",` *(zdrojové soubory)*

### Tvorba potřebných adresářů dle konvencí next-js
- SLOŽKA S PORJEKTEM
 - src
  - pages
