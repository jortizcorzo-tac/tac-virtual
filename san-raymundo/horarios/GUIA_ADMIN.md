# GUÍA DE ADMINISTRADOR — Portal de Horarios
## INEB San Raymundo

---

## ¿Cómo subir los horarios (Semana 1 y Semana 2)?

El sistema ahora soporta dos semanas de horarios de forma simultánea.

1. Guarda la imagen de la **Semana 1** con el sufijo `_s1` y la de la **Semana 2** con el sufijo `_s2`.
2. Cópialas en la carpeta correspondiente (`docentes/` o `grados/`).
3. Formatos aceptados: `.jpg`, `.jpeg`, `.png`, `.webp`

Ejemplo para el Docente 01:
- `docente_01_s1.jpg` (Imagen para Semana 1)
- `docente_01_s2.jpg` (Imagen para Semana 2)

---

## 📂 HORARIOS DOCENTES → carpeta: `horarios/docentes/`

| # | Docente           | Nombre Archivo Semana 1   | Nombre Archivo Semana 2   |
|---|-------------------|---------------------------|---------------------------|
| 1  | Docente 01       | `docente_01_s1.jpg`       | `docente_01_s2.jpg`       |
| 2  | Docente 02       | `docente_02_s1.jpg`       | `docente_02_s2.jpg`       |
| 3  | Docente 03       | `docente_03_s1.jpg`       | `docente_03_s2.jpg`       |
| 4  | Docente 04       | `docente_04_s1.jpg`       | `docente_04_s2.jpg`       |
| 5  | Docente 05       | `docente_05_s1.jpg`       | `docente_05_s2.jpg`       |
| 6  | Docente 06       | `docente_06_s1.jpg`       | `docente_06_s2.jpg`       |
| 7  | Docente 07       | `docente_07_s1.jpg`       | `docente_07_s2.jpg`       |
| 8  | Docente 08       | `docente_08_s1.jpg`       | `docente_08_s2.jpg`       |
| ...| Continúa hasta el 28 | `docente_XX_s1.jpg` | `docente_XX_s2.jpg` |

> ⚠️ Reemplaza "Docente 01" con el nombre real del docente en el código JS del index.html

---

## 📂 HORARIOS POR GRADO → carpeta: `horarios/grados/`

| # | Grado        | Nombre Archivo Semana 1 | Nombre Archivo Semana 2 |
|---|--------------|-------------------------|-------------------------|
| 1  | Primero A   | `primero_a_s1.jpg`      | `primero_a_s2.jpg`      |
| 2  | Primero B   | `primero_b_s1.jpg`      | `primero_b_s2.jpg`      |
| 3  | Primero C   | `primero_c_s1.jpg`      | `primero_c_s2.jpg`      |
| 4  | Primero D   | `primero_d_s1.jpg`      | `primero_d_s2.jpg`      |
| 5  | Primero E   | `primero_e_s1.jpg`      | `primero_e_s2.jpg`      |
| 6  | Segundo A   | `segundo_a_s1.jpg`      | `segundo_a_s2.jpg`      |
| 7  | Segundo B   | `segundo_b_s1.jpg`      | `segundo_b_s2.jpg`      |
| 8  | Segundo C   | `segundo_c_s1.jpg`      | `segundo_c_s2.jpg`      |
| 9  | Segundo D   | `segundo_d_s1.jpg`      | `segundo_d_s2.jpg`      |
| 10 | Segundo F   | `segundo_f_s1.jpg`      | `segundo_f_s2.jpg`      |
| 11 | Tercero A   | `tercero_a_s1.jpg`      | `tercero_a_s2.jpg`      |
| 12 | Tercero B   | `tercero_b_s1.jpg`      | `tercero_b_s2.jpg`      |
| 13 | Tercero C   | `tercero_c_s1.jpg`      | `tercero_c_s2.jpg`      |
| 14 | Tercero D   | `tercero_d_s1.jpg`      | `tercero_d_s2.jpg`      |
| 15 | Cuarto A    | `cuarto_a_s1.jpg`       | `cuarto_a_s2.jpg`       |
| 16 | Cuarto B    | `cuarto_b_s1.jpg`       | `cuarto_b_s2.jpg`       |
| 17 | Quinto A    | `quinto_a_s1.jpg`       | `quinto_a_s2.jpg`       |
| 18 | Quinto B    | `quinto_b_s1.jpg`       | `quinto_b_s2.jpg`       |
| 19 | Sexto A     | `sexto_a_s1.jpg`        | `sexto_a_s2.jpg`        |
| 20 | Sexto B     | `sexto_b_s1.jpg`        | `sexto_b_s2.jpg`        |

---

## 🔐 Panel de Administración

- El botón de admin es el **ícono de engranaje** (⚙️) en la esquina inferior derecha, sobre la ventanilla.
- Contraseña por defecto: `ineb2026`
- El panel ahora mostrará el estado individual de la **Semana 1** y la **Semana 2** por cada grado y maestro.
