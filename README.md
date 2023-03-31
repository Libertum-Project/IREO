# IREO

Setear en el contrato antes del despliegue el supply de NFT y maximo a mintear c/u.

Setear los address beneficiarios y los porcentajes en el constructor antes del deploy

colocar la moneda con la que se va a pagar en ADDCURRENCY

recordar en la funcion MINT que el id comienza en 0

usar el realese para enviar los fondos a las wallets que correspondan.

en la base uri colocar el IPFS donde va a estar alojado el titulo de propiedad 
(RECOMIENDO TOCAR LA FUNCION PARA QUE CADA MINTEO SUME UN NUMERO EN LA BASE URI, EJ IPFS:XXXXXXXX1.JSON, IPFS:XXXXXXXXXX2.JSON, IPFS:XXXXXXXXX3.JSON PARA PODER OTORGARLES A LOS USUARIOS SU TITULO DE PROPIEDAD A LA HORA DE MINTEAR AUTOMATICAMENTE Y QUE SEA DE ACUERDO A SU ID, actualmente el contrato envia un ipfs random sin setear y tiene una funcion para setear el base uri, con eso es suficiente para una muestra de codigo, pero para ser OPERATIVO FUNCIONAL deberian setearlo en IPFS correlativo y posteriormente escalarlo a AWS.)


