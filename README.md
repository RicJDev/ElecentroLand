<div align="center">
  <img src="./images/logo.jpg" width = 450>
  <h1>Elecentroland</h1>
</div>

Este es el proyecto que estamos escribiendo Las Víctimas de Elecentro para Algoritmos I. Consiste en un sistema de reservación para un hotel, un casino virtual (con posibles aplicaciones a un casino real), un restaurante con inventario y sitema de reservaciones, y un barcito para que puedas ir a llorar y beber después de reprobar matemáticas. Dicho sistema está pensado para implementarse en la ciudad de San Juan de los Morros, ubicada en el estado Guárico, Venezuela.

Este proyecto surgió a partir de la tradicional quema anual de sedes de Elecentro de San Juan. Viendo el potencial turístico y económico, nosotros como equipo decidimos aprovechar nuestro ingenio y capacidades para hacer algo que pueda significativamente aumentar el valor de la zona (y darnos plata, ¿por qué no?)

## Sobre la finalidad de este repositorio

Este repositorio ha servido como herramienta de colaboración durante el desarrollo del proyecto (lo cual se puede ver en el [historial de commits](https://github.com/RicJDev/Elecentroland/commits/master/)), lo que demuestra nuestra cohesión como equipo y habilidad técnica.

También representa cómo se organizarían los archivos en una implementación real, teniendo nuestros módulos separados por carpetas en una estructura jerárquica organizada, lo que facilita su revisión y comprensión.

Finalmente, este repositorio cuenta como documentación, ya que incluye la información más relevante sobre su uso y recomendaciones para llevar a cabo el proyecto (descritas en la presentación del mismo)

Si ya ha leído la presentación del proyecto es probable que no encuentre casi nada nuevo en este README. Sin embargo, se ha tratado de condensar y resumir lo más relevante para evitar repeticiones.

## Representación del proyecto como árbol de archivos

```
Electroland
│   Resort.txt
│
├───casino
│   │   Casino.txt
│   │   inicio_sesion.txt
│   │   menu_juegos.txt
│   │   registro_nuevo_usuario.txt
│   │
│   ├───juegos
│   │       Blackjack.txt
│   │       Dados.txt
│   │       Ruleta.txt
│   │       Tragamonedas.txt
│   │
│   └───tiendita
│       │   canjear_dinero.txt
│       │   comprar_fichas.txt
│       │   Tiendita.txt
│       │
│       └───dibujos
│               canjear_dibujos.txt
│               dibujos_usuario.txt
│               mostrar_dibujo.txt
│
├───hotel
│       check_out.txt
│       estadisticas.txt
│       generar_id.txt
│       Hotel.txt
│       metodo_de_pago.txt
│       registro_nuevo_cliente.txt
│       reserva_habitaciones.txt
│
├───images
│       logo.jpg
│
├───restaurante
│       agenda.txt
│       bienvenida.txt
│       manu_almuerzo.txt
│       menu_cena.txt
│       menu_desayuno.txt
│       Restaurante.txt
│
├───taberna
│       Taberna.txt
│
└───utilidades
        aleatorio.txt
        metodo_pago.txt
```
