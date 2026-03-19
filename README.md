#  Chatbot IT - Deep Learning Project

##  Descriere
Acest proiect are ca scop dezvoltarea unui chatbot bazat pe Deep Learning, capabil să ofere suport IT automat.

Chatbot-ul va analiza mesajele utilizatorilor și va identifica tipul problemei (ex: imprimantă, rețea, autentificare,etc), oferind un răspuns corespunzător.


##  Obiectiv
- Clasificarea problemelor IT pe baza textului introdus
- Oferirea unui răspuns automat pentru fiecare tip de problemă
- Reducerea timpului de răspuns în suportul IT


##  Dataset
Dataset-ul este unul custom și conține exemple de mesaje și etichetele acestora.

Exemplu:
- "nu merge imprimanta" → printer
- "nu am internet" → network
- "nu ma pot loga" → login


##  Model / Abordare
- Preprocesare text (lowercase, tokenizare)
- Vectorizare (Bag of Words)
- Model: Rețea neuronală (Dense Neural Network)
- Framework: TensorFlow / Keras


