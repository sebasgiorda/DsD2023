# DsD2023
# Venta online de productos

## Grupo
### Integrantes
* Sebastian Giordanino Formoso                 	49819
* Patricio Maccari                             	49839

### Repositorios
* [frontend app](http://hyperlinkToGihubOrGitlab)
* [backend app](http://hyperlinkToGihubOrGitlab)


## Tema
### Descripción
Esta es una plataforma de comercio electrónico especializada en la venta de productos cortados por láser. Aquí, los productos se seleccionan de un catálogo publicado por el vendedor y se pueden encargar según las necesidades del usuario. Los usuarios tienen la opción de iniciar sesión y mantener un registro tanto de sus datos personales como de las compras realizadas. El sistema se encarga de facilitar todas las etapas de la transacción, desde agregar productos al carrito hasta realizar el pago de la venta, además de mantener un registro actualizado del stock vendido y los pedidos realizados.


### Modelo
![imagen del modelo](https://github.com/sebasgiorda/DsD2023/blob/00bc7ec9c5f83264c4ff307fd615f57ce423d90f/Modelo%20de%20Dominio.drawio.png)

## Alcance Funcional 

### Alcance Mínimo

|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Vendedor<br>2. CRUD Articulo<br>3. CRUD Compra<br>4. CRUD Cliente|
|CRUD simple|1. CRUD Tipo Habitacion<br> 2. CRUD Cliente|
|CRUD dependiente|1. CRUD Compra {depende de} CRUD  Articulo y CRUD  Cliente<br>2. CRUD Compra {depende de} CRUD Vendedor|
|Listado<br>+<br>detalle| 1. Listado de compras filtrado por nroVenta, precioTotal => detalle CRUD Compra<br>|
|CUU/Epic|[CUU01- realizar venta](https://github.com/sebasgiorda/CUU1/blob/a38ab6e2a2a60549cfc512270e09a3cd38eda8f5/README.md)<br>[CUU02 - Cancelar venta](https://github.com/sebasgiorda/CUU2/blob/e34a5e36e860e7def805fb3e8f5f56ebcb012363/README.md)|
