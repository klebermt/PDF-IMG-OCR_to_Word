# Conversor de PDF a Word mediante OCR

Este conjunto de programas de Python permite convertir archivos PDF a documentos de Word (.docx) utilizando la tecnología OCR para extraer texto de imágenes.

## Librerías necesarias

Asegúrate de tener instaladas las siguientes librerías antes de ejecutar los programas:

- PyMuPDF: `pip install PyMuPDF`
- Pillow: `pip install Pillow`
- pytesseract: `pip install pytesseract`
- pytesseract también depende de Tesseract OCR. Puedes seguir las instrucciones de instalación aquí: [Tesseract OCR](https://github.com/tesseract-ocr/tesseract)

**Instalar Tesseract OCR en linux**

```
sudo apt-get install tesseract-ocr
```

## Uso

### Programa 1: `PDFReader.py`

Este programa convierte un PDF escaneado a un documento de Word. Ejecútalo de la siguiente manera:

```bash
python PDFReader.py <nombre_del_archivo.pdf>
```

### Programa 2: ImgReader.py

Este programa convierte una imagen a un documento de Word. El nombre del archivo de Word será el mismo que el de la imagen. Ejecútalo de la siguiente manera:

```
python ImgReader.py <nombre_de_la_imagen.png>
```

### Programa 3: PDF_OCR_Reader.py

Este programa convierte todas las páginas de un PDF a imágenes, aplica OCR a cada imagen y luego crea un documento de Word con el texto extraído. Ejecútalo de la siguiente manera:

```
python PDF_OCR_Reader.py <nombre_del_archivo.pdf>
```

El documento de Word resultante se guardará con el mismo nombre del archivo PDF.

