## Tarea repaso

![Diagrama de clases](/home/dam/Documentos/COD/DiagramaClasesBol17.drawio.png)

![Diagrama de flujo](/home/dam/Documentos/COD/DiagramFlujoBol17.drawio.png)

1. Generamos el .jar del programa, para ello:

    - File -> Project Structure -> Artifacts -> Jar -> From modules with dependencies
    - Seleccionar Main -> Apply -> Ok
    - Build -> Build Artifacts

2. Inicializamos repositorio
    
    - git init
    - git branch -M main
    - git add Boletin17/src README.md
    - cd out/artifacts/Boletin17_jar
    - git add Boletin17.jar
    - git remote add origin https://github...
    - git commit -m "añadiendo..."
    - git tag -a v1.0 -m "jar 1.0"
    - git push origin main
    - git push origin --tags

3. Generamos una release de esa etiqueta

4. Modificamos el código

5. Generamos nuevo .jar, para ello repetimos el paso 1

6. Añadimos el nuevo .jar y lo etiquetamos
    
    - cd out/artifacts/Boletin17_jar2
    - git add Boletin17.jar
    - git commit -m "añadiendo..."
    - git tag -a v2.0 -m "jar 2.0"
    - git push origin main
    - git push origin v2.0

7. Generamos release de la segunda etiqueta