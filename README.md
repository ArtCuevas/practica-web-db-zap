# Practica web + db + zap = security

Este repositorio contiene el código fuente y la documentación de la actividad de "práctica web + db + zap = security" de la maeteria de Aspectos de Seguridad para el Desarrollo de Sostware, la cual dentro de sus objetivos mencionados tiene el demostrar el ciclo de `construir → detectar → corregir → verificar` en una aplicación web.

---

## Descripción del Proyecto

La aplicación es un pequeño servidor Node.js con Express que se conecta a una base de datos SQLite. Se crearon deliberadamente vulnerabilidades de Inyección SQL y Cross-Site Scripting (XSS) para ser detectadas con OWASP ZAP, para posteriormente corregirlas aplicando buenas prácticas de desarrollo seguro y verificar todo con un segundo escaneo.

##  Instrucciones de Ejecución

Para ejecutar este proyecto se debe seguir los siguientes pasos::

1.  **Clonar el Repositorio:**

2.  **Instalar Dependencias:**
    Asegurarse de tener Node.js instalado. Luego, hay que ejecutar el siguiente comando en la terminal para instalar las librerías necesarias (Express, Helmet, SQLite, etc.).
    ```bash
    npm install
    ```

3.  **Iniciar la Aplicación:**
    Una vez instaladas las dependencias, hay que iniciar la aplicación:
    ```bash
    node app.js
    ```

4.  **Acceder a la Aplicación:**
    Solo hay que abrir el navegador y visitar la siguiente dirección:
    [http://localhost:3000](http://localhost:3000)

---

## Checklist de Entregables

- [x] Código fuente completo y ejecutable. 
- [x] Capturas ZAP: Sites, Alerts list, Alert detail..
- [x] Reporte (PDF) con comparativa antes y después.
- [x] `package.json` y `seed.sql` incluidos.
- [x] Instrucciones de ejecución (README).
