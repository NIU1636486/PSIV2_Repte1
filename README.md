QUÈ ÉS CADA FITXER:
1. **Imatges matricules**:
   - matricules_nosaltres
   - matricules_profe
  
2. **bd_comparativatext**:
   - bd_matricules_nosaltres
   - bd_matricules_profe
   Això quan tinguem la matricula total predicta. Juntar els caràcters predits en singular. I comparar en text. A lo imatge_profe 1 és 1234ABCD doncs ja tenir-ho en taula.

3. **proves_segmentacio.ipynb**:
  Detectar i segmentar matricules profe amb CONTOURS. No s'adapta llavors anar a per YOLO

4. **YOLO**:
   - YOLO_train_collab.zip: entrenament del YOLO amb base de dades internet + les seves labels(anotacions) + yolo11n.pt amb 20 epoques.
   - modelentrenat20: resultats del entrenament YOLO. metriques del entrenament/resultats, el més important és weights: best.pt que farem servir per predir.
   - yolo_ubi_segmentacio.ipynb: De les imatges del profe amb YOLO(best.pt) detectar la matricula i després segmentar els caracters.

5. **Dades per classificació**:
   Lletres/numeros per patrons per classificar.
   - MESPREG.ttf: la font de les lletres i numeros
   - dataugmentation.ipnyb: codi per fer el data augmentation a les lletres i numeros (rotacions)
   - DataTrain_Comprimit.zip: lletres i numeros separats després del data augmentation.

6. **CLASSIFICADOR**:
   - TrainingModel_SVC_SyntheticData.ipynb
   - TrainingModel_KNN_SyntheticData.ipynb
