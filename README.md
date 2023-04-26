# DRUGI ZADATAK

U ovom zadatku potrebno je deployati ovu aplikaciju na Azure.

Koraci:

- prijavite se na Azure portal putem web preglednika
- otvorite projekt u VS codeu
- pritisnite tipku `F1` te upišite ili odaberite iz dropdowna `Create new Web App... Advanced`
- odaberite ime svoje aplikacije
- odaberite `Create a new resource group`
- odaberite node LTS verziju (14, ali može i druge)
- odaberite windows OS
- odaberite regiju najbližu sebi (West Europe)
- odaberite `Create new App Service plan` te nakon toga opciju `FREE`
- za opciju `Select an Application Insights resource for your app` odaberite `Skip for now`
- trebao bi vam se prikazati popup `Always deploy the workspace...`, pritisnite `Yes`
- s lijeve strane bi vam se trebao u Azure ekstenziji prikazati novi resurs i unutar njega vaša aplikacija. pritisnite desni klik na `Application Settings` i odaberite `Add new setting...`
- u input zalijepite ovaj izraz `SCM_DO_BUILD_DURING_DEPLOYMENT`
- u sljedeći input upišite `true`
- zadnji korak je da pritisnete desni klik na vašu aplikaciju s lijeve strane u Azure ekstenziji i iz dropdowna odaberete `Deploy to WebApp...`
