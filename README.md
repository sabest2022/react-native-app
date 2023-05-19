
React Native Jobb App:

Det här är en React Native applikation som byggts med hjälp av Expo. Applikationen använder en extern API för att hämta information om populära jobb och geografiskt närliggande jobb. Användaren kan välja ett jobb och se alla detaljer om jobbet, samt ansöka om det direkt från appen.
Arkitektur


Projektet organiseras med hjälp av följande mappstruktur och nyckelfiler:

App-mappen: Denna mapp är hjärtat av applikationen. Här är två huvudfiler:
index.js: Denna fil är huvudingången till applikationen. Den ansvarar för att rendera appen på enheten.
_layout.js: Denna fil definierar det övergripande layoutet för applikationen. Det kan inkludera saker som navigering och globala stilar.
Jobb-details-mappen: Denna mapp finns inom app-mappen och innehåller id].js filen. Denna fil representerar en dynamisk sida för varje enskilt jobb. När en användare klickar på ett specifikt jobb, anropar id].js API:et för att hämta och visa detaljerna för det specifika jobbet.
Components-mappen: Denna mapp innehåller de olika React-komponenterna som bygger upp användargränssnittet. Varje komponent har sitt eget ansvarsområde och bidrar till att skapa ett reaktionskraftigt och interaktivt gränssnitt för användaren.
Hooks-mappen: Denna mapp innehåller anpassade React-hooks, specifikt useFetch.js. useFetch.js är en anpassad hook som hanterar anropen till API:et. Den tar hand om att göra förfrågan, hantera svarsdata och hantera eventuella fel.
.env-fil: Denna fil är nödvändig för att skydda din API-nyckel. Nyckeln lagras i denna fil och är dold för användare för att undvika eventuella säkerhetsrisker. Denna nyckel importeras sedan i filerna där den behövs för att göra API-anrop.
Andra mappar och filer:
assets innehåller alla statiska filer, till exempel bilder, som används i applikationen.
constants kan innehålla konstanta värden som används på flera ställen i applikationen.
styles innehåller alla globala och komponent-specifika stilmallar.


Installation och körning:

För att installera och köra denna app, följ stegen nedan:
Skapa en mapp, öppna mappen i VScode,
Install react nativ expo: nix create-expo-app@latest -e with-router ./
Skapa mappar och filler som krävs. 
Ladda ner Expo go, kör och test med nom start kommandon. 



copyright:
copyrith tillhör: https://github.com/adrianhajdin/project_react_native_jobs ,
jag har skrivit om koden genom en youtube utbildning av läraren. 

# Expo Router Example

Use [`expo-router`](https://expo.github.io/router) to build native navigation using files in the `app/` directory.

## 🚀 How to use

```sh
npx create-expo-app -e with-router
```

## 📝 Notes

- [Expo Router: Docs](https://expo.github.io/router)
- [Expo Router: Repo](https://github.com/expo/router)
