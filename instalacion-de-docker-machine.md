# INSTALACIÓN DE DOCKER MACHINE EN LINUX

![](/assets/docker-machine.png)

* [Instalar Docker \(docker engine\)](/instalacion.md)

* Descargar el binario de **Docker Machine** y habiliatarlo en el PATH.

      **[terminal]
      **[prompt user@server]**[path ~]**[delimiter  $ ]**[command curl -L https://github.com/docker/machine/releases/download/v0.13.0/docker-machine-`uname -s`-`uname -m` >/tmp/docker-machine && chmod +x /tmp/docker-machine && sudo cp /tmp/docker-machine /usr/local/bin/docker-machine]

* Verificar la Instalación:

  ```
  **[terminal]
  **[prompt user@server]**[path ~]**[delimiter  $ ]**[command docker-machine version]
  docker-machine version 0.12.2, build 9371605
  ```



