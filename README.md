# BotaniScanAPI
Capstone project bangkit 2023-Cloud computing

Base url of this service is: http://localhost:4000/

The service available:
Authentications

POST /authentications
PUT  /authentications
DEL  /authentications
Users

GET  /users/{userId}
POST /users
PUT  /users/{userId}
DEL is not avalable now
Predictions

POST /predictions/cassava
POST /predictions/rice
POST /predictions/tomato
History

GET  /predict/historys/
GET  /predict/historys/{historyId}
GET  /predict/historys/plant/{plantId}/
GET  /predict/historys/plant/{plantId}/disease/{diseaseId}
POST /histories
DEL  /histories/{historyId}
Classifications

POST /classifications/vegetable
Plant

GET   /plants
POST  /plants
PUT   /plants/{plantId}
GET   /plants/{plantId}
DEL   /plants/{plantId}
Diseases

GET   /diseases
POST  /diseases
PUT   /diseases/{diseaseId}
GET   /diseases/{diseaseId}
DEL   /diseases/{diseaseId}
