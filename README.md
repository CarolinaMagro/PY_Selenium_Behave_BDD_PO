
# BehaveBDDWithPageObjects 🚀

Este repositorio contiene un proyecto de automatización de pruebas utilizando **Behavior Driven Development (BDD)** con **Behave** y el patrón de diseño **Page Objects**. El objetivo del proyecto es crear una estructura de pruebas fácil de mantener y escalable, facilitando la colaboración y el desarrollo ágil.

## Tabla de Contenidos 📑

- [Estructura del Proyecto](#estructura-del-proyecto)
- [Requisitos](#requisitos)
- [Instalación](#instalación)
- [Configuración](#configuración)
- [Ejecución de Pruebas](#ejecución-de-pruebas)
- [Generación de Reportes](#generación-de-reportes)
- [Contribuir](#contribuir)
- [Licencia](#licencia)

## Estructura del Proyecto 🗂️

El proyecto está organizado en los siguientes directorios y archivos:

- **.idea/**: Archivos de configuración del IDE.
- **allure_reports/**: Reportes generados por Allure.
- **BehaveBDDBasics/**: Configuraciones básicas y ejemplos para trabajar con Behave.
- **ConfigurationData/**: Archivos de configuración y datos de prueba.
- **Logs/**: Archivos de logs generados durante las pruebas.
- **pytestlearning/**: Scripts de aprendizaje y experimentación con PyTest.
- **testcases/**: Casos de prueba implementados utilizando Behave y el patrón Page Objects.
- **venv/**: Entorno virtual de Python con las dependencias del proyecto.
- **behave/**: Implementación de las pruebas BDD con Behave.
- **requirements.txt**: Lista de dependencias de Python necesarias para el proyecto.

## Requisitos ⚙️

Para ejecutar este proyecto, necesitarás:

- Python 3.x 🐍
- Pip 📦
- Entorno virtual de Python (recomendado) 🛠️
- Herramientas de BDD (Behave) 🧪
- Allure para generación de reportes 📊

## Instalación 💻

Sigue estos pasos para configurar el proyecto en tu entorno local:

1. Clona el repositorio:

    ```bash
    git clone <URL-del-repositorio>
    cd BehaveBDDWithPageObjects
    ```

2. Crea y activa un entorno virtual:

    ```bash
    python3 -m venv venv
    source venv/bin/activate   # En Windows: venv\Scripts\activate
    ```

3. Instala las dependencias del proyecto:

    ```bash
    pip install -r requirements.txt
    ```

## Configuración 🛠️

1. Asegúrate de que todos los archivos de configuración necesarios estén en `ConfigurationData/`.
2. Configura las variables de entorno o modifica los archivos de configuración según sea necesario para tu entorno.

## Ejecución de Pruebas 🧪

Para ejecutar las pruebas automatizadas, utiliza el siguiente comando:

```bash
behave
```

Este comando ejecutará todos los casos de prueba definidos en el proyecto.

## Generación de Reportes 📊

Después de ejecutar las pruebas, puedes generar reportes usando Allure:

```bash
allure serve allure_reports/
```

Este comando abrirá un servidor local donde podrás ver los reportes detallados.

## Contribuir 🤝

Si deseas contribuir al proyecto, por favor sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza los cambios necesarios y haz commits (`git commit -m 'Agrega nueva funcionalidad'`).
4. Empuja los cambios a la rama (`git push origin feature/nueva-funcionalidad`).
5. Crea un Pull Request.

## Licencia 📄

Este proyecto está bajo la licencia MIT. Para más detalles, consulta el archivo `LICENSE`.
