# RUB-IIB-Workshops-2024

## Data
- [OpenFlat TTL](https://raw.githubusercontent.com/AlexDonkers/ofo/main/SWJ_Resources/OpenFlat/OpenFlat_Donkers.ttl)
- [OpenFlat IFC](https://github.com/AlexDonkers/ofo/blob/main/SWJ_Resources/OpenFlat/OpenFlat_Donkers.ifc)

## Tools
- GraphDB
- Visual Studio Code
- [Long list of handy LBD tools](https://github.com/SSoLDAC2024/Tools-and-handy-documents)

# Workshop 

## GraphDB
- Run GraphDB
- Create a new repository
- Import the OpenFlat TTL
- Run a SPARQL query

## Comunica
- [Comunica web client with the OpenFlat](https://query.comunica.dev/#datasources=https%3A%2F%2Fraw.githubusercontent.com%2FAlexDonkers%2Fofo%2Fmain%2FSWJ_Resources%2FOpenFlat%2FOpenFlat_Donkers.ttl&query=PREFIX%20bot%3A%20%3Chttps%3A%2F%2Fw3id.org%2Fbot%23%3E%0Aselect%20*%20where%20%7B%0A%20%20%20%20%3Fs%20%3Fp%20bot%3ABuilding%20.%0A%7D%20limit%20100)
- [Comunica web client with the OpenFlat and the OpenSmartHome](https://query.comunica.dev/#datasources=https%3A%2F%2Fraw.githubusercontent.com%2FAlexDonkers%2Fofo%2Fmain%2FSWJ_Resources%2FOpenFlat%2FOpenFlat_Donkers.ttl;https%3A%2F%2Fraw.githubusercontent.com%2FAlexDonkers%2FOpenSmartHome%2Fmain%2FopenSmartHome_Donkers.ttl&query=PREFIX%20bot%3A%20%3Chttps%3A%2F%2Fw3id.org%2Fbot%23%3E%0Aselect%20*%20where%20%7B%0A%20%20%20%20%3Fs%20%3Fp%20bot%3ABuilding%20.%0A%7D%20limit%20100)

## SPARQL Endpoints
- [Public SPARQL endpoint of the city of Florence](https://opendata.comune.fi.it/content/sparql)
- [DBpedia SPARQL endpoint](https://dbpedia.org/sparql)

## Frontend tools
- [LD-BIM](https://ld-bim.web.app/)
- [LBDviz](https://alexdonkers.github.io/LBDviz/dist/)
- [SPARQL-visualizer](https://madsholten.github.io/sparql-visualizer/)

## Python-based graph interactions
- [01_Check python version](https://colab.research.google.com/github/AlexDonkers/RUB-IIB-Workshops-2024/blob/main/01_CheckPythonInstallation.ipynb)
- [02_RDFlib](https://colab.research.google.com/github/AlexDonkers/RUB-IIB-Workshops-2024/blob/main/02_RDFlib.ipynb)
- [03_SPARQLWrapper](https://colab.research.google.com/github/AlexDonkers/RUB-IIB-Workshops-2024/blob/main/03_SPARQLWrapper.ipynb)
- [04_RDFlib + python variables](https://colab.research.google.com/github/AlexDonkers/RUB-IIB-Workshops-2024/blob/main/04_RDFlib-plus-python-variables.ipynb)

## LBDviz
- [LBDviz](https://alexdonkers.github.io/LBDviz/dist/)
- [Tutorial](https://github.com/AlexDonkers/Frontends-and-LBD/)
- [A Visual Support Tool for Decision-Making over Federated Building Information](https://link.springer.com/chapter/10.1007/978-3-031-37189-9_32)
