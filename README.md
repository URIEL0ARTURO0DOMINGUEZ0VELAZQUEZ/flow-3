# flow-3
imajenes representativas 

bueno principalmente tenemos que encender nuestro contenedor para poder utilizar nuestro Node-RED buenopara recordar con que comando se puede encender es el siguiente
**docker compose up -d**
para poder mostrar que funciono debe de aparecer de la siguienete manera.
![imagen](https://github.com/URIEL0ARTURO0DOMINGUEZ0VELAZQUEZ/flow-3/assets/136390705/3f0c1ece-d2c6-44b4-82fb-9126ff7038f2)
pero es comando enciende todos pero podemos encender el que vamos a utilizar con docker start **[id_del_contenedor_de_node_red]**
ya que esta encendido depende tu tcp pones **localhost:(numero-tcp)**
si no conocemos el tcp podemos consultarlo con nuetra terminal con comando **docker ps -a**
![imagen](https://github.com/URIEL0ARTURO0DOMINGUEZ0VELAZQUEZ/flow-3/assets/136390705/7fa3a708-ee3e-4eb2-b7cc-90a5d08d326e)

## MODIFICACIONES EN Node-RED

como anteriormente sabemos que podemos incerta de manera facil 
un ejemplo seria de la sig. manera 
![imagen](https://github.com/URIEL0ARTURO0DOMINGUEZ0VELAZQUEZ/flow-3/assets/136390705/28eccc40-e863-4757-8311-9450eea4493b)

al parecer se presta para hacer modificaciones al gusto siempre y cuando sepamos lo que quere mos hacer 

## Uso de  los siguiente contenedores Docker de MQTT, Node-Red y MySQL.

ya no es necesario de encender los contenedores si no los apagastes, en mi caso siguen encendidos

pimero tenemos que instalar las  bibliotecas si no sabes en  mi otro commit lo explico en **flow2**
en este caso instalaremos la biblioteca **mysql**
### nota:de preferencia que sean las mas actuales.
