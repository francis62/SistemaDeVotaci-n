# Bases de Datos Avanzada

Este proyecto para la catedra de Bases de Datos Avanzada consiste en un proyecto de elaboracion de un sistema de votacion con blockchain utilizando las tecnologias: Metamask, Ganache y Truffle.

## Instalacion

1. Descargar el repositorio ya sea haciendo un git clone o descargando el proyecto como un archivo .zip.

```bash
git clone https://github.com/francis62/SistemaDeVotacion.git
```

2. Instalar las tecnologias Truffle, Ganache y la extension de Metamask.

3. Abrir el proyecto y ejecutar los siguientes comandos:
```bash
npm i //para instalar todas las dependencias
```
```bash
truffle migrate //para desplegar los dos contratos necesarios
```
```bash
npm start //para iniciar live server en localhost:3000 y probar el sistema
```
4. Ya teniendo el sitio web abierto, la primera persona registrada será el administrador, el cual tiene los poderes de añadir candidatos, ver los votantes y empezar y/o finalizar una elección.

5. Luego las demás personas registradas y conectadas con su billetera mediante la extensión de metamask podrán ejercer su voto. 

