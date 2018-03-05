### Instalación de un paquete con Conda
```
$ conda install blah...
```

### Creación de un entorno con coda (un entorno, similar a un gemset)
```
$ conda create --name myenv
```

### Uso del entorno en Jupyter
Es necesario instalar el paquete ipykernel
```
$ source activate myenv # activa el entorno
$ conda install ipykernel
$ source deactivate
```

Después lanzar Jupyter
