# Modelo de aprendizaje automático que pronostica la tasa de cancelación de clientes para el operador de telecomunicaciones Interconnect 

### Introducción

Interconnet es un operador de telecomunicaciones que proporciona diferentes servicios a sus clientes, destacándose principalmente por sus planes de internet y comunicación por teléfono fijo a través de la conexión a varias líneas. Además de esto, los usuarios pueden aprovechar otros beneficios como seguridad en línea, almacenamiento de archivos en la nube, backup de datos, línea de soporte técnico, streaming de TV y películas. Por otro lado, la clientela puede elegir entre un pago mensual o firmar un contrato de 1 o 2 años. Puede utilizar varios métodos de pago y recibir una factura electrónica después de una transacción.

La empresa buscar mejorar la experiencia de sus usuarios y, de esta manera, disminuir el número de clientes que abandonan sus cuentas en Interconnect. Para esto el equipo de marketing busca pronosticar la tasa de cancelación de sus usuarios. Es así que si se descubre que un usuario o usuaria planea irse, se le ofrecerán códigos promocionales y opciones de planes especiales. Para esto la mejor opción será construir un modelo de aprendizaje automático clasificatorio que ayude a determinar la cancelación o no de cuentas, a partir de datos que recopilan la información personal, planes y contratos de cada uno de los usuarios registrados. 

### Objetivos

1. Realizar una exploración inicial de los datos y, en base a esto, preprocesarlos hasta que no se registren valores ausentes, duplicados o artefactos extraños. 
2. Investigar y encontrar patrones en los datos a través un análisis exploratorio univariado y bivariado.
3. Dividir y preparar los datos para el entrenamiento de modelos de machine learning a través de codificación, estandarización y otros métodos que se consideren pertinentes.
4. Construir, ajustar y probar varios modelos de aprendizaje automático que ayuden a clasificar a usuarios de acuerdo a la posibilidad de cancelación o no de sus cuentas en Interconnect.
5. Escoger aquel modelo que alcance un AUC-ROC de al menos 0.88 en el conjunto de prueba.
