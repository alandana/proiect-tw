proiect-tw

#INTERFATA/DESIGN

- pagina va contine cateva tab-uri, fiecare tab fiind corespunzator unei activitati(de exemplu libraria personala sau persoanele avute la urmaritori ai profilului)
- in partea de jos a ecranului vor exista o bara de cautare in documente dupa cuvant cheie, un buton de incarcare de document si eventual un buton care sa permita crearea unui folder nou
- in dreptul fiecarui document afisat in pagina, utilizatorul va avea posibilitatea de a-l adauga la favorite sau de a-l muta in cosul de gunoi

#COMPONENTE

- lista de documente
- utilizatori din follow
- buton de cautare
- buton de incarcare document
- tab pentru fiecare optiune a meniului
#API CALLS

- GET /documents
- POST /documents
- GET /documents/{id}
- DELETE /documents/v1/{document_id}/files/{file_id}
- POST /documents/{id}/trash
- POST /folders
- DELETE /folders/{id}
- GET /followers; POST /followers; PATCH /followers/{id}; DELETE /followers/{id}
- GET /search/documents

#ACTIUNILE UTILIZATORULUI

- vizualizare documente
- incarcare document
- stergere document
- follow alti utilizatori
- accept/decline cerere de follow
- cautare dupa cuvant cheie
