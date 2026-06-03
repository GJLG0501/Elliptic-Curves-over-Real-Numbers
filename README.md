# Elliptic Curves over ℝ, 𝔽ₚ y ECDH

Proyecto de la materia **MA2006B: Advanced Programming Evaluation**.

Implementación, desde primeros principios y usando **únicamente la biblioteca estándar de
Python 3.12**, de la aritmética de curvas elípticas:

1. **`EllipticCurveReal`** — ley de grupo sobre los números reales (ℝ) usando `float`.
2. **`EllipticCurveFp`** — la misma aritmética sobre un campo primo 𝔽ₚ con aritmética modular.
3. **`simulate_ecdh`** — simulación del intercambio de claves Elliptic Curve Diffie-Hellman.

> ⚠️ No se usan bibliotecas externas (sympy, numpy, cryptography, sage, etc.). Solo `math`.

## Estructura

| Archivo | Descripción |
|---------|-------------|
| `Persona1.ipynb` | Parte 1: curva sobre los reales (`EllipticCurveReal`). |
| `ecc_project.ipynb` | Entregable final integrado (Partes 1, 2, 3 y tests públicos). |

## Cómo ejecutar

Abrir el notebook en Jupyter y ejecutar **desde un kernel limpio, de arriba hacia abajo**:

```bash
jupyter notebook ecc_project.ipynb
```

No requiere instalar dependencias: todo corre sobre Python 3.12 estándar.

## Integrantes del equipo

- Nombre 1
- Nombre 2
- Nombre 3
