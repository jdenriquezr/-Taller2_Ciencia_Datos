### Taller 2 Integrantes:

Juan Diego Enriquez
Lina Maria Bejarano

## Objetivo
Diseñar un modelo de Machine Learning para predecir el valor de los apartamentos a partir de las características que ingresan los clientes en una plataforma, con el fin de disminuir los costos y tiempo de peritaje.​

## Instrucciones de Ejecución

1. Crear entorno virtual:
```bash

python3 -m venv venv_apto

```

2. Activarlo:

* **Linux/Mac:**
  
  ```bash
     
   source venv_apto/bin/activate
   
  ```
     
* **Windows:** 
```bash
   venv_aptol\Scripts\activate
```
3. Instalar dependencias:

```bash
   pip install -r requirements.txt
```
## En el repositorio se encuentra:

1. Informe ejecutivo con el nombre: Informe ejecutivo-taller2CDA_jenriquez_lmbejarano.pptx
2. Base de datos en formato .csv: apartamentos.csv
3.  Cuaderno de jupyter: Taller2CDA_jenriquezr_lmbejarano.ipynb
## Insights

1. Se evaluaron 2 modelos de machine learning Regresión lineal y XGBoost-regressor, entre estos modelos fue XGBoost. Este modelo presento un R2 de 0.85, lo que indica que explica el 85 del precio de venta de los apartamentos.
2. El modelo de ML(XGBoost) logró presentar predicciones cercanas al valor real. Lo que quiere decir que presenta buenos rendimientos en términos de predicción.
3. Las características que más aportan al precio de venta de los apartamentos  son: área, valor de administración, # de años, antigüedad, estrato y localidad.
4. En la validación del  modelo se encontró que un 35.8%  se requiere un avalúo presencial por el desfase presente entre el valor real y el valor predicho.  Esto sugiere que el ~64% no requiere de ello y va a presentar una ahorro en peritaje. Además, este valor destaca un buen rendimiento del modelo.
5. El modelo reduce costos de peritaje en 15.245.404 pesos al mes. Que representa una disminución del 53,4% del valor que se usa sin modelo ($28.500.000). 
6. Este modelo, permite una reducción de 30.491 pesos promedio por avalúo. Lo que representa un valor de $13.254.596 para predicción de valor de apartamentos al mes.
7. El modelo en general, requiere una inversión de 52 millones de pesos en infraestructura y remuneración al científico de datos. Con la reducción  anual de ~182 millones de pesos, esta inversión se recupera en menos de un año, y en un año, puede retornar valores de  ahorro en 3.5 veces la inversión  del modelo de acuerdo con el valor ROI.


## Recomendaciones  para la empresa

- Mejorar y ampliar la base de datos utilizada para el entrenamiento del modelo, podría incrementar la precisión en la estimación del precio de venta.​
- Evaluar la escalabilidad del modelo, en como puede adaptar la incorporaciónde los datos.​
- Con el pasar del tiempo se va a requerir monitoreo del modelo, por lo que se sugiere hacer un estudio al respecto para incluir el valor de esta actividad en la inversión del modelo.


