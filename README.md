
# WSL
## INTRODUCCIÓN

### ¿QUÉ ES WSL?

![wsl](https://github.com/BeaLama/SWL/assets/148747089/e32cecc8-9bc3-4cdf-a674-b9c6cb2b9ce6)

Subsistema de Windows para Linux (WSL) es una característica de Windows que permite ejecutar un entorno Linux en la máquina Windows, sin necesidad de una máquina virtual independiente ni de arranque dual. WSL está diseñado para proporcionar una experiencia perfecta y productiva para los desarrolladores que quieren usar Windows y Linux al mismo tiempo.

## INSTALACIÓN

### Para instalar WSL debemos seguir los siguientes pasos:
* En la Powershell de nuestro Windows escribiemos el comando "wsl --install"

![image](https://github.com/BeaLama/SWL/assets/148747089/abfc1eab-cfee-492f-bd4e-cfcd563a941a)

* Para la instalación de Debian utilizamos el comando "wsl --install -d Debian"

![image](https://github.com/BeaLama/SWL/assets/148747089/5810e69c-3a4b-4cbf-88fb-eaee5d092902)

* Para la instalación de Ubuntu usamos el comando "wsl --install -d Ubuntu"

![image](https://github.com/BeaLama/SWL/assets/148747089/33191236-8fa3-414a-bc25-1152898ade6e)

La instalación de Ubuntu se realizó con el primer comando.

## PROCESOS

### WSL utiliza varios procesos en segundo plano para gestionar la ejecución del entorno Linux dentro de Windows. Algunos de estos procesos son:

* **LxssManager**: Es el administrador de subsistemas de Windows para Linux.

* **WSL Distribution Launcher**: Se encarga de iniciar las distribuciones de Linux instaladas.

* **WSL Service**: Proporciona la interfaz entre el kernel de Linux y el subsistema de Windows.

* **Pico Provider**: Proporciona la integración de sistema de archivos entre Windows y Linux.

    
## REFERENCIAS

## Enlaces de referencia
* [Microsoft](https://learn.microsoft.com/es-es/windows/wsl/about)
* [ChatGPT](https://chatgpt.com/c/98a13112-d9e7-401e-a4f3-637b46bcf16d) 


## Licencia
<p xmlns:cc="http://creativecommons.org/ns#" >This work is licensed under <a href="http://creativecommons.org/licenses/by-nc/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"></a></p>
