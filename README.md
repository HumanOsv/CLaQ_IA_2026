## Inteligencia Artificial Aplicada a la Química: Desde los SMILES hasta Modelos de Machine Learning

Curso/charla docente  que recorre el pipeline completo de cheminformática y ciencia de datos aplicada a moléculas, desde la representación digital de compuestos hasta modelos predictivos de machine learning.

### Puntos importantes

**Representación molecular y SMILES**
- Formas de representar estructuras químicas en una computadora (grafos, formatos de archivo, notación lineal)
- Sintaxis SMILES: reglas, ejemplos, estereoquímica y aromaticidad
- SMILES canónico como identificador único para bases de datos moleculares

**Fingerprints moleculares**
- Codificación de moléculas como vectores binarios/numéricos
- Métodos de fingerprinting: estructura, subestructura, fragmento y propiedad
- Similitud molecular (coeficiente de Tanimoto) y entornos atómicos (ECFP/Morgan)
- Visualización del espacio químico y herramientas de cheminformática (RDKit, ChemoPy, PaDEL, CDK)

**Ciencia de Datos aplicada a química**
- Fundamentos: qué es la ciencia de datos, su relación con la IA, disciplina multidisciplinaria
- Base matemática: álgebra lineal (vectores/PCA), cálculo/optimización, estadística y probabilidad
- Ciclo de vida de un proyecto de datos, ilustrado con un pipeline QSAR real

**Machine Learning para química**
- Tipos de aprendizaje: supervisado, no supervisado, semi-supervisado y por refuerzo
- Clasificación (cribado virtual activo/inactivo) y regresión (predicción de pIC50, logP, solubilidad)
- Métricas de desempeño (accuracy, precision/recall, F1, matriz de confusión, MAE/MSE/RMSE)
- Clustering de compuestos por similitud estructural (k-means, DBSCAN, jerárquico)
- Redes neuronales de grafos (GNN) como alternativa moderna a los fingerprints fijos
- Problemas prácticos: sobreajuste, interpretabilidad/modelos caja negra, explicabilidad (XAI: LIME, SHAP) y desbalance de clases en cribado de alto rendimiento (HTS)
- Librerías clave: NumPy, Pandas, Scikit-learn, RDKit, TensorFlow/PyTorch
