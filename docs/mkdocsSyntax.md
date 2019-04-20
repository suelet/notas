# mkdocs.yml

Es el archivo que usaremos para definir la configuración del proyecto de MkDocs.

## Añadir extensiones

En MkDocs existen extensiones que nos permiten añadir funcionalidad que por defecto no existe. Para añadir una extensión basta definirla en el apartado markdown_extensions del archivo mkdocs.yml.

Un ejemplo que añade 3 extensiones:

    markdown_extensions:
      - admonition
      - toc
      - pymdownx.emoji:
          emoji_generator: !!python/name:pymdownx.emoji.to_png


!!! Danger "Título"
    Any number of other indented markdown elements.

    This is the second paragraph.