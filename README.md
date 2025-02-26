En aquest repositori trobem tot el treball del primer repte de l'assignatura MAPSIV del grup 7 format per: 

- Carlota Cortés
- Paula Macías
- Marc Puigbó
- Pol Riubrogent

A continuació detallarem que inclou aquest repositori:

**Fitxers importants:**

- **model_definitu.ipynb:** Es tracta del model definitu del nostre treball, on agrupem les diferents fases de l'algoritme.
- **MPASIV_RepteI_Grup7.pdf:** L'informe on es recull el procés i la metodologia seguida per realitzar el repte.
- **PSIV_REPTE1_PPT.ppt:** El Power Point de la presentació del treball.

**Carpetes del repositori:**

1. **Bases de dades**: La carpeta on es recullen totes les dades que hem utilitzat per realitzar el nostre repte.
   
   - matricules_nosaltres: Imatges de matricules capturades per nosaltres.
   - matricules_profe: Imatges de matricules descarregades del CV.
   - RealData_Comprimit: Imatges de caràcters alfanumèrics segmentats per la etapa de reconeixement i classificació,
   - MESPREG.ttf: Font original de la matrícula espanyola utilitzada per entrenar models.
   - bd_image_test.xlsx: Excel amb les etiquetes reals de les imatges a comparar text.
   - image_test.zip: Imatges per la comparativa de text del model definitiu.
  
3. **Localització/Segmentació:** Models i proves de segmentació i localització de matrícules.
   
   - proves_selecció_matricula.ipynb: Proves realitzades per localitar la matrícula.
   - proves_segmentació.ipynb: Proves realitzades per segmetnar la matrícula.
   - yolo_ubi_segmentació.ipynb: Model definitiu per detectar i segmentar la matrícula.
   - YOLO_train_collab.zip: entrenament del YOLO amb base de dades internet + les seves labels(anotacions) + yolo11n.pt amb 20 epoques.
   - modelentrenat20: resultats del entrenament YOLO. metriques del entrenament/resultats, el més important és weights: best.pt que farem servir per predir.
  
4. **Classificació/Reconeixement:** Models i proves de classificació de caràcters.

   - dataugmentation.ipnyb: codi per fer el data augmentation a les lletres i numeros (rotacions).
   - TrainingModel_SVC_SyntheticData.ipynb: Model de classifiació entrenat amb dades sintètiques (Data augmentation).
   - TrainingModel_KNN_SyntheticData.ipynb: Model de classificació entrenat amb dades sintètiques (Data augmentation).
   - TrainingModel_SVC_RealData.ipynb: Model de classifiació entrenat amb totes les dades.
   - TrainingModel_KNN_RealData.ipynb: Model de classifiació entrenat amb totes les dades.
   - TrainingModel_CNN_RealData.ipynb: Model de classifiació entrenat amb totes les dades.
