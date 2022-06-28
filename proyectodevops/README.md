Proyecto Devops
Integrantes:
    Cesar Gonzalez
    Jonathan Gomez
    Arnoldo Aguilar
    Giancarlo Lopez

Este proyecto trata sobre la implementacion
un droplet utilizando como base en la nube de DigitalOcean, y para provisionar se utilizo Ansible y la implementacion de la estructura en Terraform.

Crear archivo .tfvars con las variables:
token y la direccion de las llaves publica y privada.


do_token = ""
ssh_key_private = ""
droplet_ssh_key_id = ""
droplet_name = "MyBlog"
droplet_size = "s-1vcpu-1gb"
droplet_region = "nyc1"

Recursos necesarios para la elaboracion:
    1.una cuenta en digital ocean
    2.instalar terraform 
    3.instalar ansible
    4.creacion del archivo .tfvars
    5.creacion del las llaves ssh
    6.creacion del token en digital ocean para la configuracion del API.
    7.creacion del id_token con doctl

Importante: 
            Tomar en cuenta los permisos de las carpeta .ssh/


Monitoreo
    Dentro de la pagina web de Digital Ocean se encontro la opcion para la revision del droplet creado y las distintas instancias que se pueden revisar.



# proyectofinal
