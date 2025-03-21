# 🧠 Proyecto de Visualización y Análisis de Imágenes DICOM y NIfTI

![Versión](https://img.shields.io/badge/versión-1.0-blue)
![Python](https://img.shields.io/badge/Python-3.6%2B-brightgreen)
![Licencia](https://img.shields.io/badge/licencia-MIT-green)

Una herramienta potente y flexible para procesar, visualizar y analizar imágenes médicas en formato NIfTI (.nii, .nii.gz) y formato DICOM (.dcm). Ideal para investigadores, médicos y estudiantes que trabajan con imágenes de resonancia magnética.

## ✨ Características Principales

- **🔍 Visualización Avanzada:** Genera vistas de alta calidad de cortes axiales, sagitales y coronales.
- **📂 Exploración en Lote:** Procesa y visualiza automáticamente todas las imágenes de un directorio.
- **🔢 Estadísticas de Procesamiento:** Proporciona métricas sobre la cantidad y tipos de imágenes procesadas.
- **✅ Validación de Conjunto de Datos:** Verifica la presencia de imágenes correspondientes a pacientes específicos.

## 📋 Requisitos Previos

```bash
# Instalar dependencias
pip install nibabel matplotlib numpy
```

## 📁 Estructura del Proyecto

```
Notebooks
├── Dicom2Nifti.IPYNB    # Script principal para visualización
└── README.md              # Esta documentación
```

## 📝 Formato de Archivos

El sistema espera archivos NIfTI con el siguiente formato de nombre:
```
SAN_XXX_VY.nii.gz
```
Donde:
- `XXX`: Identificador numérico del paciente
- `VY`: Versión del escaneo (V1, V2, etc.)

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Para contribuir:

1. Haz un Fork del repositorio
2. Crea una rama para tu función (`git checkout -b nueva-funcion`)
3. Realiza tus cambios y haz commit (`git commit -m 'Añadir nueva funcionalidad'`)
4. Sube tus cambios (`git push origin nueva-funcion`)
5. Abre un Pull Request

## 📜 Licencia

Este proyecto es de uso libre y abierto a quien lo desee.

## 📊 Citar este Proyecto

Si utilizas este software en tu investigación, por favor cítalo como:

```
[Tu Apellido], [Inicial]. (2025). Proyecto de Visualización y Análisis de Imágenes NIfTI [Software].
GitHub: https://github.com/JPDevOpti
```

---

✨ **Desarrollado por:** Juan Pablo Restrepo | 📧 **Contacto:** Juanpablorestrepo2020@gmail.com | 🌐 **Web:** https://github.com/JPDevOpti