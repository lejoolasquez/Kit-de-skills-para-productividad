# Skills para Claude en español

Colección de skills para Claude en español: herramientas prácticas para el trabajo y la vida, listas para usar.

Un *skill* es un paquete de instrucciones que le enseña a Claude a hacer una tarea de una forma específica. Una vez instalado, Claude lo usa solo cuando detecta que aplica, sin que tengas que pedírselo.

## Catálogo

| Skill | Para qué sirve |
|---|---|
| [Conversaciones cruciales](skills/conversaciones-cruciales/) | Prepara conversaciones difíciles (jefe, equipo, pareja, amigos) con una guía corta basada en el libro *Conversaciones cruciales*. |

## Cómo instalar un skill

### En Claude.ai (web, escritorio o móvil)

1. Ve a **Releases** (columna derecha de este repositorio) y descarga el `.zip` del skill que quieras.
2. En Claude, entra a **Settings → Capabilities** y verifica que esté activada la ejecución de código y creación de archivos.
3. Ve a **Customize → Skills**, haz clic en **Upload skill** y selecciona el `.zip`.
4. Abre un chat nuevo y úsalo con normalidad. Por ejemplo: "tengo que hablar con mi jefe sobre…".

En planes Team o Enterprise, puede que un administrador tenga que habilitar los skills primero.

### En Claude Code

Copia la carpeta del skill dentro de `~/.claude/skills/`:

```bash
cp -r skills/conversaciones-cruciales ~/.claude/skills/
```

## Aviso

Los skills basados en libros resumen sus ideas con palabras propias y citan a sus autores. No reproducen el texto original ni tienen afiliación con los autores ni con las editoriales. Si te sirve el contenido, te recomiendo leer el libro.

## Licencia

Consulta el archivo [LICENSE](LICENSE).
