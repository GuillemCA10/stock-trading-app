Prototipo de aplicación web que simula una plataforma de trading de acciones, desarrollada con Python y Flask.

Los usuarios pueden crear una cuenta, iniciar sesión y gestionar un portfolio virtual con 10.000 $ en efectivo inicial.

Pueden consultar precios de acciones en tiempo real, simular compras y ventas, añadir efectivo a su cuenta y consultar su historial de transacciones.

Nota: Los precios de las acciones se obtienen a través de la API financiera de CS50. La aplicación es totalmente funcional en el momento de escribir esto,
pero esta dependencia podría dejar de funcionar en el futuro si la API es eliminada. 

Puede que migre a una alternativa pública como Yahoo Finance.

Los datos del usuario (nombre de usuario y contraseña) se almacenarán únicamente de forma local en app.db,
que se crea automáticamente en la carpeta del proyecto la primera vez que ejecutas la aplicación.
No saldrán de tu dispositivo, pero si no estás convencido, puedes usar un nombre de usuario y contraseña ficticios.

INSTALACIÓN

git clone https://github.com/GuillemCA10/stock-trading-simulator.git
cd stock-trading-simulator

CONFIGURACIÓN

Instala las dependencias necesarias:

pip install -r requirements.txt

Ejecuta la aplicación:

flask run

A continuación, abre tu navegador y ve a http://127.0.0.1:5000. La base de datos se creará automáticamente la primera vez que ejecutes la app.
