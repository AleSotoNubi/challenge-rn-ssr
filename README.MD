![screenshot](https://puu.sh/HyrmV/95c458d9d9.png)

#
&nbsp;
### ⭐️  Buscamos Colaboradores️ ⭐️ 
Buscamos Devs con ganas de sumarse a los desafios que hoy tenemos en **Nubi**.

# NubiApp Coding Challenge ☁️ &nbsp; ![easy](https://img.shields.io/badge/-medium-orangnge) ![time](https://img.shields.io/badge/%E2%8F%B0-60m-blue) 

&nbsp;
## Finalidad ✨
- Crear una app sencilla de 3 paginas en REACT NATIVE (un login, una pantalla de dashboard y una de movimientos)

&nbsp;
## Requerimientos

utilizar la informacion disponibilizada en la api mas abajo descripta
- Login (no es necesario validar datos, la api siempre te devolvera un jwt)
- dashboard
- servicios habilitados (dinamico segun "services" en el json)
- menu (dinamico segun "navigation" en el json)
- pagina de movimientos (dinamicos segun "movements" en el json)


&nbsp;
## Que esperamos una vez terminado el challenge 🏁
- un repositorio con codigo del challenge (publico)
- un .apk o .api (el que prefieras)

&nbsp;
## Que vamos a evaluar 💡
- como trabajaste el jwt
- persistencia de datos (context/redux/etc) 
- manejo de errores
- manejo de variables y scopes
- ajustable a varios dispositivos (nice to have)
 


&nbsp;
## Recursos 🌄
&nbsp;
API: https://nubitestapi.free.beeceptor.com/login
Esta api te devuelve un JWT que debes decodificar, contiene informacion del usuario, nombre, email, servicios activos, movimientos de dinero

JWT Keys: nubikey

encoder/decoder https://10015.io/tools/jwt-encoder-decoder

Ejemplo:
`{
  "email": "test@tunubi.com",
  "name": "Nubi",
  "lastName": "Wallet",
  "services": [
    "Pedir Plata",
    "Mandar plata",
    "Cargar la SUBE",
    "Recargar un celular",
    "Pagar tus servicios"
  ],
  "navigation": [
    "Inicio",
    "Tarjeta",
    "Actividad",
    "Perfil"
  ],
  "movements": [
    {
      "title": "recibiste dinero",
      "amount ": "+ $200",
      "date": "15 de abril"
    },
    {
      "title": "recibiste dinero",
      "amount ": "+ $500",
      "date": "12 de abril"
    },
    {
      "title": "beneficio nubiers",
      "amount ": "+ $2500",
      "date": "1 de abril"
    }
  ]
}`

## Las imagenes son ilustrativas, no le vamos a dar tanta importancia al diseño, si a la funcionalidad :)
![screenshot](https://i.ibb.co/34vxf5L/screen-0.png)![screenshot](https://i.ibb.co/WWkmCWs/screen-1.png)![screenshot](https://i.ibb.co/JCRV5BL/screen-2.png)
