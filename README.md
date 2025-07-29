# 🧠 Detección de Fraude con Tarjetas de Crédito — MFIN 2025

Este proyecto implementa un análisis completo de detección de fraude en transacciones de tarjetas de crédito, utilizando machine learning, validación cruzada y la ley de Benford. Forma parte del trabajo final de la materia **Introducción a Ciencia de Datos** de la Maestría en Finanzas (UTDT).

---

## 🧱 Requisitos

- Python 3.9 o superior  
- Cuenta de [Kaggle](https://www.kaggle.com/)  
- Git y GitHub configurados  
- Visual Studio Code (recomendado)

---

## ⚙️ Paso a paso para crear el ambiente

1. Clonar este repositorio:

```bash
git clone https://github.com/rbasa/fraude-tc.git
cd fraude-tc
```
2. Crear y activar el entorno virtual:
```bash
python -m venv .venv
source .venv/bin/activate     # En Windows: .venv\Scripts\activate
```
3. Instalar las dependencias:
```bash
pip install -r requirements.txt
```
4. Registrar el entorno como kernel de Jupyter:
```bash
python -m ipykernel install --user --name=mfin-fraude
```

💾 Paso a paso para obtener la base de datos

Para poder correr el programa es necesario usar la base de datos que está en Kaggle. Se puede simplemente descargar y poner el archivo dentro del directorio ./data/fraudTest.csv

⚠️ Los archivos .csv están excluidos del repositorio mediante .gitignore para evitar conflictos por su tamaño.