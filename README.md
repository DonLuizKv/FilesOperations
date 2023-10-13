# FilesOperations
Hola!, nuestra libreria presentada en este repositorio se llama FilesOperations, es un librería que esta centrada en archivos para Java.
Decidimos presentar una parte de nuestra libreria con el propósito de mejorar la recursividad de los programadores, además de hacer que no se estanquen en el desarrollo de su código, el cual complica y ralentiza su progreso.

# Importar La libreria
```
import Files.FileModifier;

```

# Inicializar File Modifier
```
FileModifier prueba = new FileModifier();
```
# 1. Escribir en el archivo
```
 prueba.writerInArchive("../ ruta del archivo / nombre del archivo.txt", "texto que se quiera digitar");
```
# 2. Crear un archivo
```
  prueba.createArchive("../ ruta del archivo / nombre del archivo.txt");
```
# 3. mover un archivo
```
  prueba.moveArchive("../ ruta del archivo / nombre del archivo.txt", "../ nueva ruta para el archivo / nombre del archivo.txt");
```
# 4. copiar un archivo
```
  prueba.copyArchive("../ ruta del archivo / nombre del archivo.txt", "../ nueva ruta para el archivo / nombre del archivo.txt");
```
# 5. borrar un archivo
```
  prueba.deleteArchive(""../ ruta del archivo / nombre del archivo.txt"");
```
# 6. leer un archivo
```
  prueba.readArchive(""../ ruta del archivo / nombre del archivo.txt"");
```
