<img src="Documents/Logo Black.png" alt="ByggKPI Logo" style="width: 200px" />  

# bsDD Norwegian Dictionaries

This project is testing the use of [buildinSMART](https://technical.buildingsmart.org/) data dictionaries ([bsDD](https://technical.buildingsmart.org/services/bsdd/)) to enrich Building Information Modelling ([BIM](https://en.wikipedia.org/wiki/Building_information_modeling)).

Three dictionaries are under test to evaluate the interaction of bsDD and integrating them with [modelling tools](https://technical.buildingsmart.org/resources/software-implementations/?filter_5=bSDD+read+API&mode=any):

[ByggKPI Nøkkeltall](https://search.bsdd.buildingsmart.org/uri/byggkpi/bkpi_noekkeltall/0.0) - The goal is to test the possibility to enrich the model at the higher and more abstract level of elements, as an example: building, floor, spaces.

[ByggKPI ByggØkonomi](https://search.bsdd.buildingsmart.org/uri/byggkpi/bkpi_byggoekonomi/0.0) - the goal is to test the possibility to enrich the elements in the model with parameters of the Norwegian standards NS3450, NS3451 and other common informative paramaters used in norwegian construction market.

[ByggKPI Beskrivelse](https://search.bsdd.buildingsmart.org/uri/byggkpi/bkpi_beskrivelse/0.0) - the goal is to test the possibility to enrich the elements in the model with parameters of the Norwegian Standard NS3420.

For the creation of this dictionaries, it was followed the instructions in [bsDD repository on GitHub](https://github.com/buildingSMART/bSDD/tree/master). The JSON files imported to bsDD can be found in the respective folder.

This dictionaries might, according to the upload instructions from buildinSMART, be switched off in case of not being maintained.
