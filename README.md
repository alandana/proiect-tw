# proiect-tw

#Interfata/design
  - pagina va contine cateva tab-uri, fiecare tab fiind corespunzator unei activitati(de exemplu libraria personala sau persoanele avute       la urmaritori ai profilului)
  - in partea de jos a ecranului vor exista o bara de cautare in documente dupa cuvant cheie, un buton de incarcare de document si             eventual un buton care sa permita crearea unui folder nou
  - in dreptul fiecarui document afisat in pagina, utilizatorul va avea posibilitatea de a-l adauga la favorite sau de a-l muta in cosul       de gunoi
#Componente
  - lista de documente
  - utilizatori din follow
  - buton de cautare
  - buton de incarcare document
  - tab pentru fiecare optiune a meniului
#API calls
  - GET /documents
  - POST /documents
  - GET /documents/{id} 
  - DELETE /documents/v1/{document_id}/files/{file_id}
  - POST /documents/{id}/trash
  - POST /folders
  - DELETE /folders/{id}
  - GET /followers; POST /followers; PATCH /followers/{id}; DELETE /followers/{id}
  - GET /search/documents
#Actiunile utilizatorului
  - vizualizare documente 
  - vizualizare documente favorite
  - incarcare document
  - stergere document
  - adaugare document la favorite
  - follow alti utilizatori
  - cautare dupa cuvant cheie
   
