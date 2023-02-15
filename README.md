Det här Repository använder ReactJS, TypeScript och TailwindCSS. Den körs också på node 18 (se .nvmrc) och har en formatterare - prettier. Om du kör detta för första gången - se till att du har nvm (nodversionshanterare).

Om du inte har nvm installerat, kör följande kommando:
`curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash`
När du har installerat nvm på din maskin, kör `nvm i` och sedan `nvm use` (för att ha rätt nodeJs-version)

När du har rätt nodversion, kör `npm i` för att få alla nödvändiga beroenden installerade

När allt är installerat, kör `npm run start` och navigera till http://localhost:3000

API:
Observera: OpenWeather API använder en API-nyckel. I arkivet hittar du en `.env.example`-fil som du behöver för att skapa en ny fil i src som du döper till helt enkelt `.env` och klistra in värdet på din API-nyckel= REACT_APP_API_KEY=nyckel (som du kan få när du registrerar dig på OpenWeather API-webbplatsen för gratis kontot).
