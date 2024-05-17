# Ejercicio 11
## Crear namespace
![image](https://github.com/stemdo-labs/kubernetes-exercices-icasado01/assets/166407751/b7aea5ad-824d-4681-9269-04d49a75c0a7)

## Modificar deployment del ejercicio 5
![image](https://github.com/stemdo-labs/kubernetes-exercices-icasado01/assets/166407751/84b6bc93-b4c0-46a4-8235-bef1da0fd999)

## Desplegar el deployment en el namespace
![image](https://github.com/stemdo-labs/kubernetes-exercices-icasado01/assets/166407751/9d0694cb-f267-4d02-a008-67d78392901c)

## Modificar etiqueta de la imagen
![image](https://github.com/stemdo-labs/kubernetes-exercices-icasado01/assets/166407751/f7f65fa5-7345-4315-bb39-49da7eb9f2e8)

## Aplicar el cambio de la etiqueta
![image](https://github.com/stemdo-labs/kubernetes-exercices-icasado01/assets/166407751/1c80c616-0fb9-4777-afc6-18112c9fc4cc)

Cuando se aplica el cambio de la etiqueta, al tener como estrategía RollingUpdate, se actualizan los pods de manera incremental sin dejar de ejecutar el servicio. En este caso se crea un nuevo pod con la imagen nueva y se deja ejecutando el pod anterior. Una vez que
el pod que hemos creado despliega la imagen, el pod antiguo se borra y se queda funcionando unicamente el pod nuevo.
