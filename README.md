* [Deliverable 1 Document]([https://docs.google.com/document/d/1nsGIeEfJcqjZ_Max3em2NcJI6Ekz9qwitJ5Ktx2cg3g/edit?usp=sharing])


# banking-app

VERY ROUGH SKETCH // Currently using flask to make UI // Used ExchangeRate-API for conversion // 

This is a application framework that the user can sign in and track their banking statements ( monthly income, bills, current savings ext.) and be able to convert all into a currency of their choosing. 


backend/
│── app.py
│── config.py
│── models.py
│── routes.py
│── database.py
│── requirements.txt
│── Dockerfile
│── venv/ 

frontend/
│── src/
│   │── components/
│   │   ├── Login.js
│   │   ├── Signup.js
│   │   ├── Dashboard.js
│   │   ├── TransactionForm.js
│   │   ├── TransactionTable.js
│   │── services/
│   │   ├── api.js
│   │── App.js
│   │── index.js
│── public/
│── package.json
│── Dockerfile


