# BirkWeb
Birk Web er en web app for å redigere av K2 Hjelpetekster.

## Avhengigheter
- Node og NPM [download](https://www.npmjs.com/get-npm) (LTS versjon)
11.06.2023: Node versjon for package er v12.xx

## Kom igang
- kjør `npm install`
- for debug. `npm run dev`
- for Build : `npm run prod` --out: dist

###
[Birk.Editor.Api](https://dev.azure.com/Smidig/Birk/_git/Birk.Editor.Api) må kjøres lokalt for å få returnert data
For å bli kvitt denne avhengigheten bør det legges til rette for å kunne kjøre opp webapp med mock data

## Pipeline
Birk.Editor.Web.CD -> Continious Integration og Deploy [pipeline](pipeline.yml)

## Miljø
| Miljø | Adresse |  
|-----------|:-----------:|  
| Dev | [http://824-web06:5001/](http://824-web06:5001/) |  
