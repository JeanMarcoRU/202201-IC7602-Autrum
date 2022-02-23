#### Jean Marco Rojas U. - Alonso Obando - 

# Preparación del entorno
    Descargar miniconda desde el siguiente enlace: https://docs.conda.io/en/latest/miniconda.html
    Realizar la instalación convencional
    Ejecutar la consola de miniconda (lo pueden hacer escribiendo miniconda en el buscador principal de windows)

## Crear un entorno con python 3.6 y activarlo
    $ conda create -n MiEntorno anaconda python=3.6
    $ conda activate MiEntorno

## Instalar kernel y jupyter notebook
    $pip install jupyter
    $conda install ipykernel
    $python -m ipykernel install --user --name MiEntorno --display-name "MiEntorno"
    
## Correrlo
    ingresar desde conda y ejecutar jupyter notebook
    
    $jupyter notebook
    
    Se abrirá jupyter notebook, entrar a la carpeta scripts y seleccionar el archivo.

## Instalar bibliotecas
    $pip install PyAudio-0.2.11-cp39-cp39-win_amd64.whl
    $pip install scipy
    $pip install IPython
    $pip install numpy
    $pip install winsound

    Si no funcioana intente con $pip3 en lugar de $pip
    OJO PyAudio-0.2.11-cp39-cp39-win_amd64.whl es para window de 64-bits y python 3.9
    Si tiene otra version de python o SO, busque su biblioteca aqui: https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio 