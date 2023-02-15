# Angular-Docker
Se ci sono errori "permission denied", aprire il terminale da "node_modules" e inserire i seguenti comandi:
- cd ..
- sudo chmod 777 node_modules/
- npm i

Per utilizzare il comando "ping", potrebbe essere necessario installare il pacchetto "iputils-ping". Per farlo, inserire i seguenti comandi:
- apt-get update
- apt-get install iputils-ping
