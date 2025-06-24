# Fondamenti di Computer Grafica a.a. 2024-2025
## Progetto in BLENDER - Aereo Americano P51 Mustang

- Modello a cui mi sono ispirato (non riprodotto fedelmente): https://www.blenderkit.com/asset-gallery-detail/295491d5-30de-4f51-9482-e109a78b1a43/
![image](https://github.com/user-attachments/assets/7d533658-96e8-42b7-a624-f2c08917ae64)

- Video timelapse al quale mi sono appoggiato per la realizzazione del modello: https://youtu.be/QG_QkEmvlHk?feature=shared

### Realizzazione del modello
1. Il cubo di partenza viene allungato e sezionato in parti, le quali diventeranno diverse componenti del velivolo;
2. Vengono creati gli stabilizzatori posteriori del velivolo: partendo da una faccia del poligono precendente, si incassa una faccia (I), che poi viene scalata per adattarla alla forma richiesta, e successivamente scalata (S) lungo l'asse X
   fino alla dimensione ideale. Una volta fatto ciò viene ulteriormente raffinata ed alla fine i vertici delle faccie posteriori (quelle che danno verso la coda) sono rimosse unendo i vertici al centro per creare la linea dell'ala.

![image](https://github.com/user-attachments/assets/b12aa867-4661-4e08-abcc-d6cc611f3d4f)

3. Viene creata la deriva (parte alta della zona posteriore del velivolo), incassando nuove facce (I) ed estrudendo (E) dalle zone posteriori del velivolo.

![image](https://github.com/user-attachments/assets/48feaec6-c777-443f-8751-3f28f253467c)

4. Allungamento e restringimento della zona anteriore del velivolo. Alzata la parte centrale che diventerà successivamente la cabina di pilotaggio.
5. Creazione dell'alloggiamento per il pilota estrudendo e scalando verso il basso (E ed S) fino alla creazione di una zona all'interno del modello.

![image](https://github.com/user-attachments/assets/6a8e48a1-2c45-4fce-b0f7-bb41a1e51079)

6. Partendo dalle parti laterali del velivolo, creazione delle due ali speculari del velivolo: prima le facce sono state scalate, poi dopo aver aggiunto un'ulteriore faccia, questa è stata scalata lungo l'asse X per creare la base delle due
   ali.

![image](https://github.com/user-attachments/assets/b9f5c1cd-eac6-4821-a053-227e8a504ece)

7. Aggiunta il cupolino anteriore del velivolo (alloggiamento motore) con elica, considerato come oggetto seperato dal corpo del velivolo (ed infatti creato a partire da un nuovo cubo, che poi è stato sezionato e ristretto fino ad avere
   la forma finale, nel quale sono state incassate le 3 eliche, duplicate a partire dalla prima superiore e poi ruotate).
   Creazione sedile posto all'interno della cabina di pilotaggio.

   ![image](https://github.com/user-attachments/assets/62f0f3df-f4e9-48e2-803e-63fd6efa80b0)

   ![image](https://github.com/user-attachments/assets/3019e59f-e1dc-4394-b409-0d718c1df2a4)

8. Aggiustamento della cabina di pilotaggio.

9. Creazione della chiusura della cabina di pilotaggio (considerato come oggetto a se stante e creato adattando il classico cubo, che è stato sezionato (CTRL + R) ed allungato tramite GRAB (G) e SCALA (S) fino a prendere la forma dell'alloggiamento.
   Successivamente è stato spostato per ricoprire la cabina.
   Animazione dell'elica anteriore (rotazione su asse Y di 720° in 40 frame)

   ![image](https://github.com/user-attachments/assets/7c4a0fcc-ad10-4ec6-8a9e-a8f7364f5ae1)

   https://github.com/user-attachments/assets/e536883d-8b59-49a7-884d-b8863a39a113

10. Si colorano le parti:
    - Per il corpo del velivolo è stato utilizzato uno shader metallizzato;
    - Per le eliche shader metallizzato nero;
    - Per la parte anteriore shader rosso;
    - Una parte delle ali e una fascia della zona posteriore colorata di giallo (per riprendere l'immagine iniziale);
    - Per la copertura della cabina è stato usato uno shader grigio scuro con della trasparenza.
  
  FILE: /RENDER/Render_Mustang_10.png

11. Conclusione del progetto con:
    - Creazione del carrello di atterraggio;
    - Creazione ruote e colore nero per le "gomme"
    - Combinazione dello shader precedentemente usato con lo shader effetto vetro per quanto riguarda la cabina di pilotaggio.
   
    FILE: /RENDER/Mustang.png

    https://github.com/user-attachments/assets/3a2e587c-f153-4f52-b0e6-4652c9e94108

