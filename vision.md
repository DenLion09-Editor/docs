# Original project vision (Spanish)

> The original vision document for the editor, kept here for reference. Authored in Spanish by the project owner. Future specs will be in English.

---

# FASE 1: Editor

> **Spec:**  
> **Prioridad:** ✅ SI (Core MVP)  
> **Estado:** Especificado

## Vision

Simple, moderno, hacer una cosa y hacerla bien.

## Features

> FASE MVP:

| Features                                 | Descripcion                                                                                                                            |
| :--------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------- |
| abrir archivos individuales              | un archivo a la vez (Ctrl + O) abre el explorador de archivos del sistema, y el archivo seleccionado es abierto en el editor.          |
| edicion base (escribir, borrar, guardar) | edicion de codigo funte con soporte multilenguage                                                                                      |
| Avilitar/Desavilitar edicion             | (Ctrl+E) Alterna entre modo de edicion y modo normal, el modo normal es el modo por defecto y no permite editar el texto de el archivo |
| edicion media (copiar, pegar, cortar)    | (Ctrl+C, Ctrl+V, Ctrl+X)                                                                                                               |
| Búsqueda y Reemplazo                     | Find & replace (Ctrl+ f)                                                                                                               |
| lsp (language serever protocol)          | Autocompletado, go-to-definition, hover documentation, signature help                                                                  |
| syntax highlinting                       | resaltado de sintaxis                                                                                                                  |
| Ir a la linea                            | (Ctrl+G)                                                                                                                               |
| linters                                  | Validacion en timepo real (configurable)                                                                                               |
| Configuracion                            | perfiles, ui, texto, keyboard shortcuts                                                                                                |

> FASE 2: Implementacion libre

| Features            | Descripcion                                                                                                                      |
| :------------------ | :------------------------------------------------------------------------------------------------------------------------------- |
| Tabs Múltiples      | Múltiples archivos abiertos simultáneamente                                                                                      |
| Git Integration     | Diff, status, blame integrados                                                                                                   |
| Breadcrumb          | Navegación de ruta de archivo                                                                                                    |
| seleccion multiple  | - (Ctrl+D) selecionar siguiente coincidencia con la seleccion actual                                                             |
|                     | - 1 click: posicionar el cursor, 2 click: seleccionar palabra, 3 clicks: selecionar linea completa                               |
| edicion multiple    | - ALt+Shift+ arrastrar cursor para editar multiples lineas en forma de rectangulo                                                |
|                     | - Ctrl+Backspace: borrar palabra completa hacia atras                                                                            |
|                     | - Ctrl+Del: Borrar palabra completa hacia adelante                                                                               |
| navegacion avanzada | (arow left, arow up, arow down, arow right) mueven el cursor un caracter en la direccion de la flecha                            |
|                     | Ctrl+(arow left, arow up, arow down, arow right) mueven el cursor una palabra en la direccion de la flecha                       |
|                     | Shift+Ctrl+(arow left, arow up, arow down, arow right) mueven el cursor una palabra en la direccion de la flecha y la selecciona |
| Format Code         | Formateo automático por lenguaje                                                                                                 |
| Color Themes        | solporte a color themes persosnalizables y mas configuraciones de composicion (tranparencias y efectos de difuminado)            |
