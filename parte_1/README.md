# Parte 1

<img width="802" height="541" alt="robot" src="https://github.com/user-attachments/assets/4fc71853-b4c3-41cf-95a0-cc3d06d7297f" />

# Blender — Chuleta de atajos

## 1. Modo Objeto (Object Mode)

| Atajo | Función |
|---|---|
| `X` | Eliminar objeto |
| `R` | Rotar objeto |
| `G` | Mover objeto |
| `S` | Escalar objeto |
| `X / Y / Z` | Restringir la transformación a un eje |
| `H` | Ocultar objeto |
| `Shift + A` | Añadir o generar objetos |
| `Shift + clic` | Seleccionar varios objetos |
| `Ctrl + clic` | Selección múltiple según el contexto |

---

## 2. Modo Edición (Edit Mode)

### Transformaciones y geometría

| Atajo | Función |
|---|---|
| `G` | Mover elementos |
| `S` | Escalar elementos |
| `E` | Extruir geometría |
| `I` | Insertar caras (*Inset Faces*) |
| `Ctrl + R` | Añadir cortes a la malla (*Loop Cut*) |
| `M` | Unir vértices mediante el menú *Merge* |
| `Ctrl + B` | Biselar aristas (*Bevel*) |
| `Ctrl + Shift + B` | Biselar vértices |
| `Alt + Shift + S` | Transformar la selección en una esfera (*To Sphere*) |
| `F` | Crear una cara o arista a partir de la selección, según el contexto |

### Modos de selección

| Atajo | Función |
|---|---|
| `1` | Selección de vértices |
| `2` | Selección de aristas |
| `3` | Selección de caras |
| `Alt + clic` | Seleccionar un bucle de aristas (*Edge Loop*) |
| `Shift + clic` | Añadir elementos a la selección |

### Herramientas especiales

- **Bridge Edge Loops:** conecta dos bucles de aristas creando caras entre ellos.
- **Loop Cut (`Ctrl + R`):** añade cortes a la geometría.
- **Bevel (`Ctrl + B`):** crea biseles en las aristas.
- **Vertex Bevel (`Ctrl + Shift + B`):** crea biseles en los vértices.
- **To Sphere (`Alt + Shift + S`):** transforma la selección para darle una forma esférica.

---

## 3. Modificadores (Modifiers)

### Array — Matriz

Duplica un objeto varias veces siguiendo una disposición determinada.

**Usos habituales:**
- Crear ruedas dentadas.
- Repetir objetos en línea.
- Generar patrones y elementos repetitivos.
- Distribuir objetos alrededor de un círculo mediante un objeto de referencia y los ajustes correspondientes.

### Curve — Curva

Adapta la geometría de un objeto a lo largo de una curva, siguiendo su forma y recorrido.

**Usos habituales:**
- Adaptar una rueda dentada u otros elementos repetidos a una trayectoria circular.
- Crear objetos que sigan una curva determinada.
- Distribuir geometría a lo largo de caminos curvos.

---

## 4. Resumen de atajos esenciales

| Acción | Atajo |
|---|---|
| Mover | `G` |
| Rotar | `R` |
| Escalar | `S` |
| Eliminar | `X` |
| Extruir | `E` |
| Insertar caras | `I` |
| Cortar la malla | `Ctrl + R` |
| Biselar aristas | `Ctrl + B` |
| Biselar vértices | `Ctrl + Shift + B` |
| Añadir objetos | `Shift + A` |
| Ocultar objetos | `H` |

---

## Consejos

- Después de pulsar `G`, `R` o `S`, pulsa `X`, `Y` o `Z` para restringir la operación a un eje.
- Usa `Shift` para añadir elementos a una selección.
- Usa `Alt + clic` sobre una arista para seleccionar un bucle de aristas.
- Pulsa `F3` para buscar herramientas por su nombre.
- Recuerda que los atajos pueden variar según la versión de Blender, la configuración y el contexto de selección.
