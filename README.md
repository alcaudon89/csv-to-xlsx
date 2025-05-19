# CSV to XLSX Converter / Convertidor de CSV a Excel

> **Bilingual documentation**: English / Español
> 
---
### 📄 Description

A lightweight, client-side web tool that converts CSV files to Excel (.xlsx) format entirely in the browser. No data is sent to any server—your files stay local to your computer.

### ⚙️ Features

* **In-browser conversion**: Uses [SheetJS](https://github.com/SheetJS/sheetjs) to parse CSV and generate `.xlsx`.
* **Custom delimiter**: Specify any single-character separator.
* **Advanced CSV parser**: Respects quoted fields and escaped quotes.
* **Auto-filters & frozen header**: Excel output comes with filters enabled and the first row frozen.
* **Dynamic column widths**: Columns adjust to content length.
* **Debug console**: Visual log of parsing steps for development and troubleshooting.
* **Analytics**: Integrated with Matomo for usage statistics (self-hosted).

### 🚀 Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/alcaudon89/csv-to-xlsx.git
   ```
2. Copy `index.html` (and any assets) to your web server or subdomain root (e.g., `csv.yourdomain.com/public_html`).
3. Ensure SSL is configured if serving over HTTPS.

### ▶️ Usage

1. Open `https://csv.yourdomain.com` in your browser.
2. Select a CSV file and enter the delimiter (default is `,`).
3. Click **Convertir a Excel**.
4. Download your `.xlsx` file.

### 🐞 Debugging

* Open the **Debug Console** panel to inspect parsing logs.
* Remove or hide the debug panel in production by commenting out its HTML and calls to `debug(...)`.

### 🤝 Contributing

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/my-change`).
3. Commit your changes (`git commit -m "Add my feature"`).
4. Push to the branch (`git push origin feature/my-change`).
5. Open a Pull Request.

### 📄 License

This project is licensed under the [MIT License](LICENSE).

---

### 📄 Descripción

Herramienta web ligera que convierte archivos CSV a formato Excel (`.xlsx`) completamente en el navegador. Ningún dato se envía al servidor: tus archivos permanecen locales en tu equipo.

### ⚙️ Características

* **Conversión en navegador**: Usa [SheetJS](https://github.com/SheetJS/sheetjs) para parsear CSV y generar `.xlsx`.
* **Delimitador personalizado**: Permite especificar cualquier carácter separador.
* **Parser avanzado de CSV**: Respeta campos entre comillas y comillas escapadas.
* **Auto-filtros y cabecera congelada**: El Excel resultante incluye filtros y la primera fila congelada.
* **Anchos de columna dinámicos**: Las columnas se ajustan al contenido.
* **Consola de depuración**: Registro visual de pasos de parseo para desarrollo.
* **Estadísticas**: Integración con Matomo para métricas de uso (autohospedado).

### 🚀 Instalación

1. Clona el repositorio:

   ```bash
   git clone https://github.com/alcaudon89/csv-to-xlsx.git
   ```
2. Copia `index.html` (y activos si los hay) al directorio raíz de tu servidor o subdominio (p.ej., `csv.tudominio.com/public_html`).
3. Asegura que SSL esté configurado si sirve vía HTTPS.

### ▶️ Uso

1. Abre `https://csv.tudominio.com` en tu navegador.
2. Selecciona un archivo CSV y escribe el delimitador (por defecto, `,`).
3. Haz clic en **Convertir a Excel**.
4. Descarga tu archivo `.xlsx`.

### 🐞 Depuración

* Abre el panel de **Debug Console** para ver los registros de parseo.
* Oculta o elimina el panel de debug en producción comentando su HTML y las llamadas a `debug(...)`.

### 🤝 Contribuir

1. Haz un fork del repositorio.
2. Crea una rama de característica (`git checkout -b feature/mi-cambio`).
3. Realiza tus commits (`git commit -m "Agrega mi característica"`).
4. Sube la rama (`git push origin feature/mi-cambio`).
5. Abre un Pull Request.

### 📄 Licencia

Este proyecto está licenciado bajo la [Licencia MIT](LICENSE).
