**Actividad** **sobre** **GitHub** **y** **Android** **Studio**

> ● **Título:** Actividad de Configuración y Uso de GitHub con Android
> Studio ● **Nombre** **del** **Alumno:** Julián David Alcalá Forero
>
> **●** **Correo** **del** **Alumno:** **alu.179498@usj.es**
>
> ● **Asignatura:** Tecnologías Software Avanzadas para Dispositivos
> Móviles ● **Profesor:** Juan José Hernandez Alonso

**1.** **Requisitos** **Previos**

> \- Se ha utilizado mi cuenta personal de GitHub, creada anteriormente
> para este ejercicio.
>
> \- Ya he creado un proyecto inicial en Android Studio y a continuación
> mostraré el proceso de vinculación entre GitHub y mi proyecto.

**2.** **Desarrollo** **de** **la** **Actividad**

> **2.1.** **Habilitar** **el** **control** **de** **versiones** **en**
> **mi** **proyector** **de** **Android** **Studio**

Nos dirigimos a la barra superior y seleccionamos **VCS** **\>**
**Enable** **Version** **Control** **Integration**. Luego, elegimos
**Git**.
<img width="1081" alt="Captura de pantalla 2024-12-22 a las 15 39 21" src="https://github.com/user-attachments/assets/9fd45501-1ec8-49ed-8983-d51c7d65d713" />
![3cuyt1lb](https://github.com/user-attachments/assets/9d974c32-0d82-4c0d-8dc3-3d2f590763d4)

Esto hará que todos los archivos aparezcan en rojo, indicando que aún no
han sido agregados al repositorio local. Para solucionarlo, ejecutamos
en la terminal el comando:

> **-** **git** **add** **.**

Esto agregará todos los archivos.

En la pestaña de **Git**, se pueden realizar diversas operaciones tanto
en el repositorio local como en el remoto.

![za1z00m2](https://github.com/user-attachments/assets/65691aa4-f468-4480-bce2-5bf554edce14)


**2.2** **Commit** **Inicial:**

Para iniciar el proyecto, se realizó un **commit** que registra el
primer cambio en el repositorio local. Este paso establece un punto de
partida claro y garantiza que todos los archivos iniciales queden
guardados y documentados, facilitando el seguimiento de futuras
modificaciones.

![ao10zma0](https://github.com/user-attachments/assets/7d470bdb-3b5b-478a-b837-f0bf6e27c1b1)

Posteriormente, se enlaza el repositorio local con el repositorio remoto
creado previamente en GitHub, copiando la URL del repositorio remoto.

![fsxab2hw](https://github.com/user-attachments/assets/5f6f22e3-5858-4a31-b89f-42b57209ed64)

En **Android** **Studio**,desde la pestaña **Git**, seleccionamos **Manage** **Remotes** y
agregamos la URL del repositorio.

![d50zqsfr](https://github.com/user-attachments/assets/8f4534e0-ff5f-4918-910a-6d655d36b949)

![hjiueabx](https://github.com/user-attachments/assets/c8406c3a-9b3c-4242-b5df-c7b2a6583cb5)

**2.3** **Sincronización** **con** **GitHub:**

Una vez realizado el enlace, el repositorio local se sincroniza con el
remoto. Para ello:

> ● En la pestaña **Git**, seleccionamos la opción **push**.
>
> ● Al verificar en GitHub,
> observamos que el proyecto remoto se ha actualizado con los últimos
> cambios del repositorio local.

![a51n124k](https://github.com/user-attachments/assets/4256568d-9905-4cfa-9cfd-eaeeaa5e725a)

**2.4** **Creación** **de** **una** **Rama** **(Branch):**

Con el proyecto sincronizado en remoto y local, se crea una rama llamada
**develop** para desarrollar una vista de login en XML.

Para crear una rama en **Android** **Studio**:

> ● Desde la pestaña **Git**, seleccionamos **New** **Branch** y
> realizamos un **checkout** a la nueva rama.

![c25fytbr](https://github.com/user-attachments/assets/f76848b9-6407-4d26-8b50-4168c55c77dc)

![kswkauwi](https://github.com/user-attachments/assets/fec47e01-dff2-432e-b45c-00b052bc8d71)

A partir de este momento, la
vista del proyecto cambia a la rama **develop**, como se observa en la
esquina superior izquierda de Android Studio.

**2.5** **Desarrollo** **y** **Commit** **del** **Login** **en**
**XML:**

Se diseñó una interfaz de login en XML de forma ilustrativa.

Tras realizar los cambios, se
llevó a cabo un **commit** para guardar los avances en la rama
**develop** tanto en local como en remoto.
![vhowhczn](https://github.com/user-attachments/assets/753b87a2-45cf-40b9-a735-bd48a18b15bb)

![pvybjxek](https://github.com/user-attachments/assets/7ff3da09-45ea-445b-b74d-f67f6a53c8ed)

**2.6** **Creación** **de** **Pull** **Request** **(PR)** **y**
**Fusión** **de** **Cambios:**

En GitHub, se indica que existen cambios en la rama **develop** que aún
no se han fusionado con **main**.

![mvvmybfv](https://github.com/user-attachments/assets/1163d671-ed45-4401-b64f-cf4d8db8f6c9)

El siguiente paso es comparar ambas ramas (**develop** y **main**),
verificar que no existan conflictos y proceder a crear una **Pull**
**Request**.

![51xneb43](https://github.com/user-attachments/assets/09f67eff-d490-4511-8053-c2c78438783e)

Tras la revisión, se realizó
el merge de los cambios de **develop** a **main**.

![vma4ji35](https://github.com/user-attachments/assets/48f8a48d-24e4-44ff-869f-cf420b5c50db)

![1jz1ypca](https://github.com/user-attachments/assets/f67180a5-b991-46e0-bd4a-c62afe6d734d)

Como podemos verificar en Github, en la rama **main** ya se encontrarán
los cambios de **develop.**

![f4kgnqep](https://github.com/user-attachments/assets/7a43f3b6-a914-46f7-b681-0b30ed4754c8)

**2.7** **Actualización** **Local** **(Pull):**

Una vez fusionados los cambios, se realiza un **pull** para traer los
últimos cambios de la rama **main** remota a la rama **main** **local**.
![cx30aupb](https://github.com/user-attachments/assets/03db57c3-5f5c-4bf0-aab4-d4805375a119)


**3.Visualización** **y** **Comprensión**

Se ha generado un diagrama con la extensión **GitGraph** de Visual
Studio Code que muestra el flujo de trabajo.

![2jlb53fs](https://github.com/user-attachments/assets/360080d9-55a8-45f0-aa46-f83c0c975607)

Hay dos ramas activas:

> \- **main** (rama principal, en azul)
>
> \- **develop** (rama de desarrollo, en rosa) -

La rama **develop** fue creada desde **main** y se hizo un **merge** de
**develop** a **main** después de realizar cambios.

> \- **Initial** **Commit** es el primer **commit** del repositorio y
> representa el punto de partida del proyecto.
>
> \- Se realizó un **commit** en la rama **develop** con el mensaje
> “login xml”.
>
> \- Después de finalizar el desarrollo en la rama **develop**, se creó
> un **Pull** **Request** para fusionar los cambios en la rama **main**.
>
> \- El **merge** se realizó correctamente, consolidando los cambios de
> **develop** en **main**.




