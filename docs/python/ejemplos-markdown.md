# 🎨 Ejemplos de Estilos Markdown

Esta página muestra **todos los estilos y características** disponibles en Material for MkDocs.

---

## 📝 Admonitions (Callouts)

Las admonitions son bloques especiales para destacar información:

!!! note "Nota Importante"
    Esta es una nota informativa con el estilo `note`.

!!! tip "Consejo Útil"
    Este es un consejo con el estilo `tip`. ¡Muy útil para dar recomendaciones!

!!! warning "Advertencia"
    Esto es una advertencia con el estilo `warning`. ⚠️

!!! danger "Peligro"
    Este es un mensaje de peligro con el estilo `danger`. 🚨

!!! success "Éxito"
    Operación completada con éxito. ✅

!!! info "Información"
    Información adicional relevante.

!!! example "Ejemplo"
    ```python
    def ejemplo():
        return "Hola Mundo"
    ```

??? question "Admonition Colapsable"
    Este bloque está colapsado por defecto. ¡Haz click para expandir!
    
    Puedes incluir cualquier contenido aquí:
    
    - Listas
    - Código
    - Tablas

???+ abstract "Abierto por Defecto"
    Este bloque colapsable está **abierto por defecto** gracias al `+`.

---

## 🎨 Formato de Texto

### Estilos Básicos

- **Texto en negrita**
- *Texto en cursiva*
- ***Texto en negrita y cursiva***
- ~~Texto tachado~~
- ==Texto resaltado==
- H~2~O (subíndice)
- 2^10^ (superíndice)

### Listas de Tareas

- [x] Tarea completada
- [x] Otra tarea hecha
- [ ] Tarea pendiente
- [ ] Otra por hacer

---

## 💻 Bloques de Código

### Python con números de línea

```python linenums="1" title="ejemplo.py"
def saludar(nombre):
    """
    Función que saluda a una persona.
    
    Args:
        nombre (str): Nombre de la persona
    """
    print(f"¡Hola, {nombre}!")  # (1)!
    return True

# Llamada a la función
saludar("Pablo")  # (2)!
```

1.  Imprime el saludo en consola
2.  Llamamos a la función con el nombre "Pablo"

### JavaScript

```javascript title="app.js"
const calcular = (a, b) => {
    return a + b;
};

console.log(calcular(5, 3)); // Resultado: 8
```

### SQL

```sql title="consulta.sql"
SELECT 
    usuarios.nombre,
    COUNT(proyectos.id) as total_proyectos
FROM usuarios
INNER JOIN proyectos ON usuarios.id = proyectos.usuario_id
GROUP BY usuarios.nombre
ORDER BY total_proyectos DESC;
```

### Resaltado de líneas específicas

```python hl_lines="2 3"
def funcion_ejemplo():
    # Estas dos líneas están resaltadas
    variable = "importante"
    return variable
```

### Código inline

El comando `pip install mkdocs-material` instala Material for MkDocs.

---

## 📊 Tablas

### Tabla Básica

| Lenguaje | Nivel | Años de Experiencia |
|----------|-------|---------------------|
| Python   | ⭐⭐⭐⭐ | 2 años              |
| HTML/CSS | ⭐⭐⭐⭐ | 2 años              |
| SQL      | ⭐⭐⭐   | 1 año               |

### Tabla con Alineación

| Izquierda | Centro | Derecha |
|:----------|:------:|--------:|
| Texto     | Texto  | Texto   |
| Más texto | Centro | 100€    |

---

## 🔗 Enlaces y Referencias

- [Enlace externo a Google](https://google.com)
- [Enlace interno a plantilla](../templates/plantilla-proyecto.md)
- [Enlace con referencia][1]

[1]: https://mkdocs.org

---

## 📑 Pestañas (Tabs)

=== "Python"

    ```python
    print("Hola desde Python")
    ```

=== "JavaScript"

    ```javascript
    console.log("Hola desde JavaScript");
    ```

=== "Ruby"

    ```ruby
    puts "Hola desde Ruby"
    ```

---

## 🔑 Teclas del Teclado

Presiona ++ctrl+alt+del++ para reiniciar.

Para copiar: ++ctrl+c++

Para pegar: ++ctrl+v++

---

## 📝 Listas de Definiciones

Python
:   Lenguaje de programación de alto nivel, interpretado y de propósito general.

MkDocs
:   Generador de sitios web estáticos orientado a documentación de proyectos.

Markdown
:   Lenguaje de marcado ligero para crear texto formateado.

---

## 📐 Diagramas Mermaid

### Diagrama de Flujo

```mermaid
graph LR
    A[Inicio] --> B{¿Condición?}
    B -->|Sí| C[Acción 1]
    B -->|No| D[Acción 2]
    C --> E[Fin]
    D --> E
```

### Diagrama de Secuencia

```mermaid
sequenceDiagram
    participant U as Usuario
    participant S as Sistema
    participant BD as Base de Datos
    
    U->>S: Solicitar datos
    S->>BD: Consultar
    BD-->>S: Retornar resultados
    S-->>U: Mostrar datos
```

---

## 🎯 Iconos y Emojis

### Emojis

:smile: :heart: :rocket: :fire: :star: :+1:

### Iconos Material

:material-account: :material-github: :material-python: :fontawesome-brands-html5:

---

## 📦 Contenido en HTML

<div style="background: linear-gradient(90deg, #667eea 0%, #764ba2 100%); padding: 20px; border-radius: 10px; color: white; text-align: center;">
    <h3>Bloque HTML Personalizado</h3>
    <p>Puedes usar HTML directamente para estilos avanzados.</p>
</div>

---

## ✏️ Texto Crítico/Revisión

Texto normal {--texto eliminado--} {++texto añadido++} {==texto resaltado==} {~~texto~>corregido~~}

---

## 📌 Abreviaciones

La HTML es el lenguaje base de la web.

El CSS permite estilizar HTML.

*[HTML]: HyperText Markup Language
*[CSS]: Cascading Style Sheets

---

## 🔢 Notas al Pie

Esto es una frase con una nota al pie[^1].

Otra frase con otra nota[^2].

[^1]: Esta es la primera nota al pie.
[^2]: Y esta es la segunda nota al pie con más detalles.

---

!!! success "¡Todos los estilos Markdown!"
    Esta página demuestra las capacidades completas de Markdown con Material for MkDocs. ¡Úsala como referencia para tus proyectos!
