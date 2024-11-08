# Wireframe_app_FIGMA
Preparació del wireframe de l'aplicació de seguiment d'assistències i horaris d'un centre d'educacció. 
Hi ha tres tipus d'usuaris: Alumne, Professor, i Administrador. D'aquesta manera, hi ha tres planols, que es mostren depenent del tipus de compte que té l'usuari. 
La funció scroll està en ment, però les pantalles es mostren amb els afegits mínims per tal de mostrar tot en conjunt. Les llistes poden tenir una llargaria molt més amplia, junt amb els altres afegits. 

## Wireframe comú
Pantalles compartides entre els diferents tipus de comptes. Aquestes no varien sense importar quin usuari siguis. 

### Pantalla de Log in
Mostrada abans que l'usuari entri dins el seu compte. Mostra el nom del centre (l'escrit dins la pantalla és d'exemple per a veure com es mostra), a més del seu logo per a una completa identificació. Sota hi ha dos seccions en que l'usuari introdueix les seves dades per a tal d'identificar-se. Si aquestes no son correctes, no se li permet accés. Si l'usuari s'ha oblidat de la contrasenya, hi ha un botó que envia un correu al email que s'ha introduït en la primera secció. 

![imatge](https://github.com/user-attachments/assets/f7f671a2-1974-4b20-afbe-ef6307d50c9c)

### Pantalla de compte
Mostra les dades de l'usuari -foto de perfil, email, nom, i contrasenya (amagada)- a més del tipus de compte que té. Permet la modificació de tant el nom d'usuari com la contrasenya. 

![imatge](https://github.com/user-attachments/assets/5372c516-baab-486e-a9a0-36bffba817ef)

## Wireframe d'usuari
Pantalles exclusives a l'usuari*, que mostren a aquest el seguiment de la seva assistència, a més d'analisis d'aquesta. 

### Pantalla d'inici
L'usuari veu el seguiment de l'horari d'avui. Mostra un grafic de totes les hores i les raons d'assistència o falta (justificada, retard, no justificada...). També hi ha un gràfic que reculls les classes a les que ha assistit i a quines no. 

![imatge](https://github.com/user-attachments/assets/8a850376-055c-4c1d-bea4-eedd7f34fcc7)

### Pantalla d'analisis
Amb una funcionalitat molt semblant que la pantalla d'inici, les úniques diferències son la pestanya que permet controlar el temps que utilitzen els gràfics, i la petita secció que hi ha al final de la pantalla. Aquesta secció mostra el precentatge d'hores a les que l'usuari a assistit (tot hi que no va per assignatures).

![imatge](https://github.com/user-attachments/assets/5a5bdd47-4dc9-4a9c-b74a-543077121670)

## Wireframe de professorat
Pantalles exclusives al professorat**.

### Pantalla de passar llista
Pantalla amb que els professors passen l'assistència de les diferents classes. Es selecciona el grup amb la llista desplegable (tot i que el professor també pot escriure el nom un cop està desplegada). Un cop es selecciona, el professor té accés complet a la llista de tots els alumnes, i pot seleccionar l'opció que descriu la situació del l'alumne respecte a la seva assistència. Al final de tot, hi ha un botó que guarda totes les dades un cop el professor a acabat. 

![imatge](https://github.com/user-attachments/assets/8fd1d909-c067-465d-b112-f22d05d70181)

### Pantalla d'assistència
Mostra els resultats de les llistes que s'han passat. Per a triar-ho, el professor escull la classe i la data en que es va passar (les dues es desplegüen, però el professor pot escriure per a fer la cerca més ràpida). Es mostra un gràfic que engloba tots els tipus d'assistències que va haver en aquell moment, juntament amb els alumnes. Hi ha un botó que permet editar l'assitència en cas que el professor cometes un error. 

![imatge](https://github.com/user-attachments/assets/b7a3bbd1-ecaa-4127-ade6-871398f38cea)

### Pantalla de nou horari
Quan els professors passen a encarregar-se d'una nova classe, usen aquesta pantalla per a afegir-la a la llista d'assistència. Es demana el nom de la classe, que pot ser desde l'aula fins a l'assignatura i curs. El professor ha d'introduïr els horaris en que la classe es du a terme, i també els diferents alumnes que assistiran. No hi ha límit d'hores i alumnes fora de les opcions disponibles. A baix de tot de la pantalla, un botó crea el nou horari un cop el professor ha introduït totes les dades que necessita. 

![imatge](https://github.com/user-attachments/assets/88cd064d-faef-4b5f-bf56-928afc163717)

## Wireframe d'administrador
L'administrador és un tipus d'usuari que té accés a totes les accions possibles, i, per tant, té tant les pantalles de l'alumne(*) com les del professorat(**). Les seves accions s'obeeixen per sobre de les de professorat i alumne, i poden modificar processos que aquests hagin fet anteriorment. 

### Pantalla d'inici
L'única diferència que hi ha entre aquesta i la del professorat es que l'administrador veu les classes de tot els professors, i el seu gràfic mostra l'assistència de tots els alumnes del centre segons l'horari.

![imatge](https://github.com/user-attachments/assets/de56bdaa-1d54-4823-a708-865b1ea24386)

### Pantalla d'analisis, visió d'alumne.
Seguint el patró de la pantalla anterior, l'única gran diferència entre aquesta i la pantalla d'anàlisis de l'alumne es que l'administrador pot escollir l'alumne que es mostra. 

![imatge](https://github.com/user-attachments/assets/cb9b6655-09cb-4b63-b0b8-1a28ed866283)


### Pantalles d'analisis, visió de professorat. 
Aquestes pantalles son virtualment idèntiques a aquelles del professorat. Les pantalles "passar llista" i "asistència" només tenen un rang més ampli d'usuaris als que poden aplicar els funcionaments, mentre que "nou horari" no té cap tipus de canvis. 

![imatge](https://github.com/user-attachments/assets/5047199b-664c-4cd2-9824-b83411ff254b)
