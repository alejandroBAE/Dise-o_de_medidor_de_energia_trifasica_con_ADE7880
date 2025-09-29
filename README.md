# Dise-o-de-medidor-de-energ-a-trif-sica-con-ADE7880
El siguiente proyecto es personal, el cual surge como variante de mi tesis de grado. El objetivo es diseñar un producto IoT robusto para la industria.

Este dispositivo se planea instalar en motores trifásicos, el cual incorpora un integrado ADE7880 que permite realizar todo el procesamiento de señales necesario para mediciones de energía activa, aparente total, cálculos de valor eficaz (RMS), así como mediciones de energía reactiva, factor de potencia y la distorsión armónica.

En el informe adjunto se detalla el proceso de diseño del acondicionamiento de señal para conectar un sensor de corriente sct-013 de 30A/1V al ADE7880. Donde se construyo un dispositivo de prueba y se probo con motores de 5, 10, 15 y 50 caballos de fuerza (HP), bajo condiciones de trabajo a carga máxima. Con estas pruebas se buscaba verificar la señal entregada por el sensor y el acondicionamiento para asi no superar los niveles máximos admitidos por el ADE7880.

<img width="357" height="491" alt="image" src="https://github.com/user-attachments/assets/1139651d-017b-4cce-a608-2fce2375b1ec" />

En la siguiente imagen se observa el dispositivo de prueba en campo:

![IMG_20250806_084716](https://github.com/user-attachments/assets/e59b6058-89fd-4930-aa40-4f6b774771fa)

Con los resultados obtenidos se procedió a continuar con el diseño del esquemático del dispositivo (aun en proceso) donde se incluye aislamiento para la alimentación y las comunicaciones. A continuación se presenta el diagrama de bloques y algunas capturas del diseño en altium designer:

<img width="1365" height="820" alt="image" src="https://github.com/user-attachments/assets/30c0ac62-78b9-4670-acea-224db40b39fd" />

<img width="1475" height="723" alt="image" src="https://github.com/user-attachments/assets/4bc4e86d-c9ed-4da0-8e18-6abb9c839453" />
<img width="1428" height="734" alt="image" src="https://github.com/user-attachments/assets/6c57e401-0f0e-4450-b662-40af125139ba" />
<img width="944" height="742" alt="image" src="https://github.com/user-attachments/assets/7f566837-9abe-443c-bb5c-15e5605d5a07" />
<img width="1064" height="695" alt="image" src="https://github.com/user-attachments/assets/14b28750-b88c-41fe-82cd-57825c491025" />
<img width="948" height="731" alt="image" src="https://github.com/user-attachments/assets/e114a5a1-455f-4f90-ac5d-ed350f7eef07" />


