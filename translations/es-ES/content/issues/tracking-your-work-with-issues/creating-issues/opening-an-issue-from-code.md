---
title: Abrir una propuesta desde el código
intro: Puedes abrir una nueva propuesta desde una línea específica o líneas de código en un archivo o solicitud de extracción.
permissions: People with read permissions can create an issue in a repository where issues are enabled.
redirect_from:
  - /github/managing-your-work-on-github/managing-your-work-with-issues-and-pull-requests/opening-an-issue-from-code
  - /articles/opening-an-issue-from-code
  - /github/managing-your-work-on-github/opening-an-issue-from-code
versions:
  free-pro-team: '*'
  enterprise-server: '*'
  github-ae: '*'
topics:
  - Pull requests
---

Cuando abres una propuesta desde el código, la propuesta contiene un fragmento de código que muestra la línea o rango de código que elegiste. Solo puedes abrir una propuesta en el mismo repositorio donde se almacena el código.

![Fragmento de código representado en una propuesta abierta desde el código](/assets/images/help/repository/issue-opened-from-code.png)

{% data reusables.repositories.administrators-can-disable-issues %}

{% data reusables.repositories.navigate-to-repo %}
2. Ubica el código que deseas hacer referencia en una propuesta:
    - Para abrir una propuesta acerca de un código en un archivo, navega hasta el archivo.
    - Para abrir una propuesta acerca de un código en una solicitud de extracción, navega hasta la solicitud de extracción y haz clic en {% octicon "diff" aria-label="The file diff icon" %} **Files changed (Archivos modificados)**. Luego, desplázate hasta el archivo que contiene el código que deseas incluir en tu comentario y haz clic en **Ver**.
{% data reusables.repositories.choose-line-or-range %}
4. Hacia la izquierda del rango de código, haz clic en {% octicon "kebab-horizontal" aria-label="The horizontal kebab octicon" %}. En el menú desplegable, da clic en **Referenciar en nuevo informe de problemas**. ![Menú Kebab con opción para abrir una propuesta nueva desde una línea seleccionada](/assets/images/help/repository/open-new-issue-specific-line.png)
{% data reusables.repositories.type-issue-title-and-description %}
{% data reusables.repositories.assign-an-issue-as-project-maintainer %}
{% data reusables.repositories.submit-new-issue %}

### Leer más

- [Crear una propuesta](/github/managing-your-work-on-github/creating-an-issue)"
- "[Obtener enlaces permanentes a los archivos](/github/managing-files-in-a-repository/getting-permanent-links-to-files)"
- "[Crear un enlace permanente a un fragmento de código](/github/managing-your-work-on-github/creating-a-permanent-link-to-a-code-snippet)".
