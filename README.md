[clase1_python_basico.ipynb](https://github.com/user-attachments/files/34611825/clase1_python_basico.ipynb)
# promedios-de-calificaciones-VSC
calculador de promedio de calificaciones actividad de onmex
{
 "cells": [
  {
   "cell_type": "code",
   "execution_count": 1,
   "id": "081f1946-10c9-4ceb-932a-86bdc75641b9",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Hola Data Science\n"
     ]
    }
   ],
   "source": [
    "print('Hola Data Science')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 2,
   "id": "f0a2cf6e-f067-4744-800c-376ccac76879",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "sergio 25 8.7\n"
     ]
    }
   ],
   "source": [
    "# ejemplo de variables\n",
    "nombre = \"sergio\"\n",
    "edad = 25\n",
    "promedio = 8.7\n",
    "print(nombre, edad, promedio)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 4,
   "id": "d508685d-e580-4fb3-bb34-fc729e22837d",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "el promedio es 8.0\n"
     ]
    }
   ],
   "source": [
    "# suma y promedio de calificaciones\n",
    "cal1 = 9\n",
    "cal2 = 8\n",
    "cal3 = 7\n",
    "promedio = (cal1 + cal2 + cal3) / 3\n",
    "print(\"el promedio es\", promedio)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 5,
   "id": "28f62eda-ccdd-4ec6-8a45-fc36391f40ab",
   "metadata": {},
   "outputs": [
    {
     "name": "stdin",
     "output_type": "stream",
     "text": [
      "escribe tu nombre:  sergio\n",
      "escribe tu primera calificacion:  9\n",
      "escribe tu segunda calificacion:  8\n",
      "escribe tu tercera calificacion:  7\n"
     ]
    },
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "hola sergio tu promedio es: 8.0\n"
     ]
    }
   ],
   "source": [
    "nombre = input(\"escribe tu nombre: \")\n",
    "cal1 = float(input(\"escribe tu primera calificacion: \"))\n",
    "cal2 = float(input(\"escribe tu segunda calificacion: \"))\n",
    "cal3 = float(input(\"escribe tu tercera calificacion: \"))\n",
    "\n",
    "promedio = (cal1 + cal2 + cal3) / 3\n",
    "print(\"hola\", nombre, \"tu promedio es:\", promedio)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 6,
   "id": "98ceec01-42b7-49f2-afb4-ccc28ff32d36",
   "metadata": {},
   "outputs": [
    {
     "name": "stdin",
     "output_type": "stream",
     "text": [
      "escribe tu nombre:  sergio\n",
      "escribe tu primera calificacion:  9\n",
      "escribe tu segunda calificacion:  8\n",
      "escribe tu tercera calificacion:  7\n"
     ]
    },
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "hola sergio tu promedio es: 8.0\n",
      "¡felicidades! estas aprobado\n"
     ]
    }
   ],
   "source": [
    "# programa para calcular promedio y mostrar si esta aprobado o reprobado\n",
    "\n",
    "# paso 1: pedir el nombre del usuario\n",
    "nombre = input(\"escribe tu nombre: \")\n",
    "\n",
    "# paso 2: pedir tres calificaciones\n",
    "cal1 = float(input(\"escribe tu primera calificacion: \"))\n",
    "cal2 = float(input(\"escribe tu segunda calificacion: \"))\n",
    "cal3 = float(input(\"escribe tu tercera calificacion: \"))\n",
    "\n",
    "# paso 3: calcular el promedio\n",
    "promedio = (cal1 + cal2 + cal3) / 3\n",
    "\n",
    "#paso 4: mostrar el resultado con condicion\n",
    "print(\"hola\", nombre, \"tu promedio es:\", promedio)\n",
    "\n",
    "if promedio >= 6:\n",
    "    print(\"¡felicidades! estas aprobado\")\n",
    "else:\n",
    "    print(\"lo siento, estas reprobado\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "a6c14cf4-3d1c-48cd-ae6c-7a13a7e316f8",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.14.7"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
