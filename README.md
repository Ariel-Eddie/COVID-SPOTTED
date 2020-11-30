# COVID-SPOTTED
Notebook of the Deep Learning Project

L'objectif de ce projet à été la création de modèles d'apprentissage supervisé (deep learning) pour la détection automatique d'une pneumonie developpée à cause de l'infection par la COVID-19 en maximisant la précision de détection. Pour cela, une base de données publique a été utilisée (https://www.kaggle.com/tawsifurrahman/covid19-radiography-database) contenant un mélange de 219 clichés radiographiques de patients positifs au COVID-19, de 1341 clichés radiographiques de patients positifs à une infection virale respiratoire déclenchée par un autre virus que le COVID-19 et finalement 1345 clichés radiographiques de patients sains. Il est à noté que ce projet a été entièrement réalisé sous le langage de programmation Python et grâce à l'utilisation de librairies utiles à l'avancée de ce projet.

Le présent notebook est constitué de 3 principales parties :
- Exploration des données
- Visualisations
- Classification.

La classification est constituée de plusieurs sous parties :
- Architectures CNN & Lenet
- Transfert learning VGG16 & resnet50
- Features extraction avec VGG16 + Logistic Regression/SVC/Random Forest
