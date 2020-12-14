# Clase 1 - 9/12/2020
## Clonar

Podemos clonar cualquier repositorio al que tengamos acceso utilizando la url que podemos obtener de su pagina principal y escribiendola en el siguiente comando:

    git clone <url>

## Configurar git en nuestra computadora

Necesitamos configurar nuestro nombre de usuario y email para trabajar con git en el archivo de configuracion a nivel global. Lo podemos hacer utilizando los comandos:
    git config --global user.name <username>
    git config --global user.email <email>

Podemos confirmar los cambios utilizando el siguiente comando para ver la lista de variables:
    git config --global -l

Podemos borrar cualquier variable y su valor utilizando el siguiente comando:
    git config --global --unset <variableName>

