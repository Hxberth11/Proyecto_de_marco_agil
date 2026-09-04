# Proyecto Marco Ágil - Calculadora Python

Este proyecto es una aplicación de calculadora básica desarrollada en Python, siguiendo las mejores prácticas de marcos de trabajo ágiles, control de versiones con Git Flow y adhesión estricta al estándar PEP 8.

## Funcionalidades
- **Suma (`add`):** Realiza la adición de dos números.
- **Resta (`subtract`):** Realiza la sustracción de dos números.
- **Multiplicación (`multiply`):** Calcula el producto de dos números.
- **División (`divide`):** Realiza la división con validación para evitar división por cero.
- **Potencia (`power`):** Calcula la potencia de un número elevado a un exponente.

## Estándares de Código y Linter
El proyecto utiliza `flake8` para garantizar el cumplimiento de las normas de estilo PEP 8.
Para ejecutar la verificación del linter localmente:

```bash
python -m flake8 calculator.py