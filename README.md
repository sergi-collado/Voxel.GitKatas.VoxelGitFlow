# Voxel.GitKatas.VoxelGitFlow

### *Repositorio de las katas para Voxel Git Flow*

**Branches configurados:**
- *develop*
- *master*

**Behaviors configurados:**
- *develop* bloqueado para push directo
- *master* bloqueado para push directo
- *Pull Request* aprobadas por 1 persona en ambos branches

**Preparación de las katas:**

fork del repositorio por el usuario que hace la kata (no comitar en este repositorio!)

***

* #### Kata 1: Flow directo
Pasos a seguir en esta kata:
1. Crear un nuevo branch *exercise1* basado en **_develop_**
2. Modificar fichero *File01.txt* añadiendo las siguientes filas (ordenadas donde corresponda):

```
01.1: SomeNewLine 01.1    
02.1: SomeNewLine 02.1    
02.2: SomeNewLine 02.2
```

3. Añadir el fichero *SomeDir/File06.txt* con el mismo contenido que *SomeDir/File05.txt*
4. Operaciones Git necesarias para hacer commit del branch *exercise1* y obtenerlo en GitHub
5. Crear **_Pull Request_** del branch *exercise1*
6. **_Code Review / Reintegración_** del *Pull Request* en **_develop_** y eliminación del branch *exercise1* en GitHub

***

* #### Kata 2: Flow con conflictos (resolubles en GitHub)
Pasos a seguir en esta kata:
1. Crear nuevo branch *exercise2a* basado en **_develop**_
2. Modificar fichero *File02.txt* añadiendo las siguientes filas (ordenadas donde corresponda):

```
01.1: SomeNewLine 01.1    
02.1: SomeNewLine 02.1    
02.2: SomeNewLine 02.2
```

3. Añadir el fichero *SomeDir/File06.txt* con el mismo contenido que *SomeDir/File05.txt*
4. Operaciones Git necesarias para hacer commit del branch *exercise2a* y obtenerlo en GitHub
5. Crear **_Pull Request_** del branch *exercise2a*
6. Crear nuevo branch *exercise2b* basado en **_develop**_
7. Modificar *File02.txt* añadiendo las siguientes filas (ordenadas donde corresponda):

```
01.1: SomeNewLine 01.1
02.1: SomeNewLine 02.1
02.3: SomeNewLine 02.3
03.1: SomeNewLine 03.1
04.1: SomeNewLine 04.1
```

8. Añadir el fichero *SomeDir/File06.txt* con el mismo contenido que *SomeDir/File05.txt*, pero sustituyendo las líneas **02** a **04** por:

```
02: SomeOtherLine 02
03: SomeOtherLine 03
04: SomeOtherLine 04
```

9. Operaciones Git necesarias para hacer commit del branch *exercise2b* y obtenerlo en GitHub
10. Crear **_Pull Request_** del branch *exercise2b*
11. **_Code Review / Reintegración_** del *Pull Request* del branch *exercise2a* en **_develop_** y eliminación del branch en GitHub
12. **_Code Review / Reintegración_** del *Pull Request* del branch *exercise2b* en **_develop_** y eliminación del branch en GitHub
13. **_Resolución de conflictos ocasionados en 12_**

