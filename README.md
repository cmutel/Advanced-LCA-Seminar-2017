# Advanced LCA Seminar 2017

This is the course material and notebooks used in the ETH Zürich PhD seminar on Advanced LCA taught by Chris Mutel in 2017.

## Demand model

Reports used to generate demand totals and profiles:

* [Die Energieperspektiven für die Schweiz bis 2050](http://www.bfe.admin.ch/themen/00526/00527/06431/index.html?lang=de&dossier_id=06421)
* [EU Reference Scenario 2016](https://ec.europa.eu/energy/sites/ener/files/documents/ref2016_report_final-web.pdf)
* [OEMOF demandlib](https://github.com/oemof/demandlib)

In `data`:

* Electricity demand per sector 2030.xlsx
* Electricity mix 2030_Import.xlsx

I used the reference  scenario from the EC for the imports and the same matching as for the marginal mixes.

## Spatial Resolution

6 regions, divided by population and our own subjective choices.

* Zurich: Zurich (17.7%)
* Bern: Bern + Luzern + Nidwalden + Oberwalden (17.9%)
* Ost: St. Gallen + Graubünden + Glarus + Thurgau + Schaffhausen + Appenzell I/A + Zug + Schwyz + Uri (14.5%)
* Basel: Aargau + Basel L/S + Solothurn (16.8%)
* South: Vaud + Wallis + Ticino (17.5%)
* Jura: Geneva + Neuchâtel + Jura + Fribourg (12.4%)

[Creating the six regions from Swiss cantons](https://gist.github.com/cmutel/a2e0f2e48278deeedf19846c39cee4da).
