# 🚀 Investigación OSINT sobre Ebroker Insurance Technologies, S.A.

📌 **Autor**: Eduardo Blanco Bielsa ~ UO285176

Este repositorio contiene los archivos de soporte y el código principal de la investigación OSINT (Open Source Intelligence) aplicada a **Ebroker Insurance Technologies, S.A.**.  

>[!Warning]
>_La investigación real es propiedad de Ebroker. Los datos aquí presentes han sido generados aleatoriamente mediante scripts en Python, permitiendo replicar una investigación sobre empresas de distintos tamaños sin comprometer información real._  

Todas las imágenes de personas y logos han sido creadas con [Perchance.AI](https://perchance.org/ai-human-generator).  


## 🛠️ Configuración y Uso  

### 1️⃣ Instalar Neo4j Desktop  
Descarga e instala [Neo4j Desktop](https://neo4j.com/download/).

### 2️⃣ Abrir Neo4j Desktop  
Ejecuta el siguiente comando en la terminal:  

```sh
./neo4j-desktop-1.6.1-x86_64.AppImage --no-sandbox &
```
### 3️⃣ Crear una base de datos en Neo4j
1. Crear un nuevo proyecto
2. Crear una nueva base de datos
3. Anotar las credenciales por defecto:

```sh
URI: <TU_URI> (Típicamente: bolt://localhost:7687)
Usuario: <TU_USUARIO> (Típicamente: neo4j)
Contraseña: <TU_CONTRASEÑA>
```

4. Iniciar la base de datos
5. Abrir Neo4j Browser

### 4️⃣ Configurar y ejecutar Jupyter Notebook
#### 🔸 Opción 1: Usando un entorno virtual (Recomendado)

```sh
# Crear y activar el entorno virtual
python3 -m venv /path/to/uo285176_tfg_env
source /path/to/uo285176_tfg_env/bin/activate
pip install notebook

# Navegar al directorio del proyecto y ejecutar Jupyter
cd /path/to/TFG
jupyter-notebook
```

#### 🔸 Opción 2: Sin entorno virtual

```sh
cd /path/to/TFG
jupyter-notebook
```

### 5️⃣ Instalar las librerías necesarias

```sh
pip install -r /path/to/TFG/requirements.txt
```

### 6️⃣ Abrir el notebook de la investigación

Busca y abre `osint_investigation.ipynb` en Jupyter Notebook.

## 📊 Ejemplo de Resultados

### 🔍 Estructura del Grafo

![Grafo](https://github.com/user-attachments/assets/69ebb283-40dc-4469-b913-69410db2f60b)

### 👥 Empleados por departamento

![Empleados](https://github.com/user-attachments/assets/0ba4eaae-9027-49ec-8020-4469134d07c0)

### 🌐 Plataformas Sociales más comunes

![Plataformas Sociales](https://github.com/user-attachments/assets/dfe95b63-0b8d-49f4-b5fb-eeb108a118e1)

### 📢 Empleados con sus Perfiles Sociales

![Perfiles Sociales](https://github.com/user-attachments/assets/1c869a98-461b-4d39-bc7b-fcb31beefb6d)

### 🔓 Leaks y filtraciones

![Leaks](https://github.com/user-attachments/assets/f768c59f-8871-47f0-880e-01eed029e330)


![image](https://github.com/user-attachments/assets/99c3ffb8-4637-4e3e-b58b-373c17b2bf16)

