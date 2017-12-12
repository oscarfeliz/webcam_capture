1- Abrir una consola

2- Instalarse el CMake a través de la siguiente instrucción:
	
	sudo apt-get install cmake


3- Instalarse el OpenCV si no está instalado a través de la siguiente instrucción:
	
	sudo apt-get install libopencv-dev


4- Descargar a tu repositorio de GitHub el siguiente programa a través del botón Fork:
	
	https://github.com/beta-robots/webcam_capture.git


5- Clona en tu máquina el repositorio a través de la instrucción:
	
	git clone https://github.com/my_github_name/webcam_capture.git

	por ejemplo, en mi caso mi repositorio es oscarfeliz, escribiría:

	git clone https://github.com/oscarfeliz/webcam_capture.git


6- En la carpeta webcam_capture crea un directorio "build" y accede de a él a través de una consola


7- Dentro del directorio teclea "cmake .." para compilar


8- Si todo ha ido correcto teclea "make"

9- Si todo ha ido correcto teclea "./webcam_capture" y se te activará la cámara.
