# Data-driven-models-for-human-structure-interaction-based-on-MLP-and-NARX-neural-networks
NARX and MLP models for modeling humans in the Human-Structure Interaction (HSI) phenomenon. This repository includes clear instructions for implementation.


INSTRUCTIONS FOR RUNNING THE NARX AND MLP MODELS / INSTRUCCIONES PARA EJECUTAR LOS MODELOS NARX Y MLP

--- English ---
Below are the instructions for running the NARX and MLP models for the Human-Structure Interaction (HSI) phenomenon.
MATLAB and Simulink must be installed to execute these files.

To use the NARX model:
1. Open the file Enternamiento5_Humanos.mlx
2. In the code, set the variable 'entrenar' to 1 to train the model. If you want to test the NARX model, set 'entrenar' to a value different from 1.
3. The .txt files in this folder contain vertical and horizontal acceleration records for nine humans. Assign a number from 1 to 9 to the variable 'Human_select' to use the anthropometric data of the selected human.

This model will provide predictions of the structural response in time and phase for one of the nine humans considered in this study.

To use the MLP model:
1. Open the file M5_TipoAutoenc.mlx
2. In the code, set the variable 'entrenar' to 1 to train the model. If you want to test the MLP model, set 'entrenar' to a value different from 1.
3. The .txt files in this folder contain vertical and horizontal acceleration records for nine humans. Assign a number from 1 to 9 to the variable 'Human_select' to use the anthropometric data of the selected human.
4. To view the architecture of this model, set the variable 'view_net' to 1.

--- Español ---
A continuación se presentan las instrucciones para ejecutar los modelos NARX y MLP en el fenómeno de Interacción Humano-Estructura (HSI).
Debe tener instalado MATLAB y Simulink para correr estos archivos.

Para usar el modelo NARX:
1. Abra el archivo Enternamiento5_Humanos.mlx
2. En el código, asigne el valor 1 a la variable 'entrenar' para entrenar el modelo. Si desea realizar la prueba del modelo NARX, asigne a 'entrenar' un valor diferente de 1.
3. Los archivos .txt dentro de esta carpeta contienen los registros de aceleración vertical y horizontal de nueve humanos. Asigne un número del 1 al 9 a la variable 'Human_select' para usar los datos antropométricos del humano seleccionado.

Con este modelo obtendrá la predicción de la respuesta estructural en tiempo y fase para uno de los nueve humanos considerados en este estudio.

Para usar el modelo MLP:
1. Abra el archivo M5_TipoAutoenc.mlx
2. En el código, asigne el valor 1 a la variable 'entrenar' para entrenar el modelo. Si desea realizar la prueba del modelo MLP, asigne a 'entrenar' un valor diferente de 1.
3. Los archivos .txt dentro de esta carpeta contienen los registros de aceleración vertical y horizontal de nueve humanos. Asigne un número del 1 al 9 a la variable 'Human_select' para usar los datos antropométricos del humano seleccionado.
4. Si desea ver la arquitectura de este modelo, asigne el valor 1 a la variable 'view_net'.
