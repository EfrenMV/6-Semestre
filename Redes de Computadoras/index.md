### Modulo 4.- Conexión física
Puede ser inalambrica o alambrica mediante ondas de radio.

**Routers inalambricos**
**Tarjetas de Interfaz de red (NIC)**
Podemos tener NIC Ethernet y/o NIC Wlan, esto dependiendo del dispositivo y que tan nuevo es.

Por ejemplo los dispositivos moviles no tienen una NIC Ethernet.

### Capa Física
Manejado mediante tramas en las cuales van pasando por capas donde por medio del encapsulamiento van empaquetandose en una sola unidad, comunicandose con las capas superiores u inferiores.

Pdu: Unidad de datos utilizado en el modelo Osi

### Modulo 5.- Sistemas numericos

**Direcciónes binarios e IPv4**
- 32 Bits de Longitud
- Comienzan como binarios (1 y 0) -> Se 
- Convierten a decimales

Binarias:
1000101.1010101000.1010001.10001

Notación decimal
192.168.10.10

| 64 | 32 | 16 | 8 | 4 | 2 | 1 |
| -- | -- | -- | - | - | - | - |
|    |    |    |   |   |   |   |

**Direcciónes tipo ipv6**
- 128 Bits de Longitu
- Cada 4 bits -> 1 digito exadecimal
- No distinguen entre minusculas y mayusculas

**Dirección mark**
D8-C0-A6-4E-CD-13

### Capa de Red o Osi 3
Este maneja el <u>PDU de paquetes</u>

**Direccinamiento de dispostivios fianles**
Permite intercambiar datos a través de redes a los <u>dispositivos finales</u> (Celulares, PC etc..), estos dispositivos fianles deben tener una Ip unica

- **Servidor de hcp:**
Asigna las redes a los dispositivos, estos sin dublicarlos. 

**Encapsulamiento**
Realizado por el origen donde se le agrega la ruta y el numero para saberlo idenficar, mientras que el destino lo desempaqueta

**Desencapsulación**
Salto: Mover los paquetes por varios ruters hasta llegar a destino.
El host de destino sabra que es el cuando su ip coincida con la ip de destino

### Modulo 6.- Enlace de datos
### Modulo 8.- Encapsulación Ip 

Esto mediante la PDU de la capa de transporte y el PDU de la capa de red se encapsula la ip para ser conciderado un paquete.

**Caracteristicas de IP**
Protocolo con sobrecarga baja.
Diseñado para rastrear ni administrar el flunjo de paquetes funciones de la capa TPC

**TCP**:
Encargado de retener la información, como cuando se descarga algo, este le dice a la Ip que vuelva a mandar la información cuando un paquete llega dañado o simplemente no llega.

- Sin conexión:
    Es como mandar datos sin notificar al destinatario.
- Menor esfuerzo
    No necestia los campos adicionales en el encabezado para mantener una conexión estableceida.

    No garantiza que todos los pauqtes que se envian se reciben (Es poco confiable).

- Medios independientes
    No puede administrar ni recuperar paquetes no recibidos o dañados.

    Puede que los paquetes lleguen dañados, no lleguen o fuera totalmente, si pasa esto el protocolo TCP se encarga de solucionar esto.
- Fobre, Fibra Optica, Conección inalambrica
    Puede transferise por cualquiera de esta

 **Destiempo**
 Esto puede ser provocado cuando no se envian por la misma ruta y uno puede llegar mas rapido que otro

Caracteristica de la red: 
**Unidad de transmisión máxima(MTU):** Es el tamaño maximo de PDU que cada medio puede transportar

**Capas de enlaces de datos**
Utilizando dirección Marck
D8-C0-A6-4E-CD-13
OUI: Identificador unico de organización, siendo los primeros D8-C0-A6 (Fabricante)

**Fragmentación**
Divide los paquetes Ip para viajar en medio con una MTU
No se puede fragmentar una ipv6


- **Capa Osi de transporte**
Envía segmentos para ser encapsulados en un paquete IPv4 o IPv6

### 8.2.2 Campos de encabezado de paquete ipv4
