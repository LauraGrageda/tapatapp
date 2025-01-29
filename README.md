# Projecte Tapatapp 
- [Descripció del Projecte](Informació/descripcio.md)

- [Requeriments tècnics](Informació/Requeriments.md)

## Prototip 1
![Diagrama](<Prototip 1/diagramaPrototip1.png>)

## HTTP Request & Response

- [Request](HTTP/http.request.md)

- [Response](HTTP/http.response.md)


## Definició dels EndPoints del WebService
Definició dels EndPoints del Servei Web:

Què necessitem per cada End-point

- <b>Descripció</b>: Servei que consulta si existeix un User per Username.
- <b>HOST</b>: 192.168.144.63:10050
- <b>End-point (URL)</b>: http://192.168.144.63:10050/tapatapp/getuser
- <b>Method</b>: GET
- <b>Tipus de petició</b>: HTTP GET amb paràmetres inclosos a la URL.
- <b>Parametres que necessita la petició</b>: Username & email (String).
- <b>Exemple d'URL</b>: http://192.168.144.63:10050/tapatapp/getuser?username=laura&email=lala@gmail.com
- <b>Resposta</b>: Si l'usuari existeix, el servei retorna: 
         
    ```"Hello, Im " + username + " with email: " + email```

    Si l'usuari no existeix, retorna:    

    ```Usuari no trobat```

