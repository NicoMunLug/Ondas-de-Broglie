# Manual de uso

## Calculadora de dualidad onda–partícula · De Broglie & Heisenberg

Esta aplicación web es una **calculadora educativa de física cuántica**. Te permite calcular dos cosas y entender qué significan:

1. La **longitud de onda de De Broglie** (λ) de cualquier partícula u objeto.
2. La **incertidumbre mínima de Heisenberg** (Δp) a partir de la precisión con que conocés la posición.

Además, interpreta automáticamente tus resultados con un "semáforo de escala" que te dice si tu objeto se comporta de forma cuántica o clásica, y muestra una onda animada de fondo que cambia según tus valores.

No necesitás instalar nada: se abre en cualquier navegador (computadora, tablet o teléfono).

---

## 1. Vista general de la pantalla

Al abrir la página vas a encontrar, de arriba hacia abajo:

- **Encabezado con onda animada.** La onda de fondo cambia su "estiramiento" en tiempo real según los valores que vayas ingresando. Es solo visual, no hace falta tocar nada ahí.
- **Dos calculadoras lado a lado** (en pantallas chicas se ven una debajo de la otra):
  - Izquierda: *Longitud de onda de De Broglie*.
  - Derecha: *Incertidumbre de Heisenberg*.
- **Semáforo de escala**, debajo de las calculadoras, que interpreta el resultado de De Broglie.
- **Botón de información (ⓘ)** en la esquina de cada calculadora, que abre la explicación completa de la fórmula.

Los resultados se calculan **solos, a medida que escribís**. No hay botón de "calcular".

---

## 2. Cómo escribir los números

Esto aplica a todos los campos de la app:

- Podés usar **notación científica** con la letra `e`. Por ejemplo, `9.109e-31` significa 9,109 × 10⁻³¹.
- Podés escribir el separador decimal como **punto o como coma**: `2.2` y `2,2` funcionan igual.
- Los resultados se muestran en **notación científica con exponente**, por ejemplo `3.31 × 10⁻¹⁰ m`.
- Si ves un guion (**—**) en lugar de un resultado, significa que falta un dato o que el valor ingresado no es válido (por ejemplo, un cero o un texto). Revisá los campos.

---

## 3. Calculadora de De Broglie (longitud de onda λ)

Responde a la pregunta: *¿qué tan "ondulatoria" es tu partícula?* Cuanta más masa o más velocidad tenga, más corta es su longitud de onda.

### Los dos modos de entrada

Arriba de la calculadora hay un selector con dos botones. Elegí el que más te convenga:

- **Masa y velocidad** (modo por defecto): ingresás la masa en kilogramos y la velocidad en metros por segundo. La app calcula sola la cantidad de movimiento (p = m·v) y luego la longitud de onda.
- **Cantidad de movimiento**: si ya conocés el momento `p` (en kg·m/s), ingresalo directamente y la app se salta el primer paso.

### Pasos

1. Elegí el modo (Masa y velocidad / Cantidad de movimiento).
2. Escribí los valores en los campos.
3. Leé el resultado en el recuadro **"Longitud de onda λ"**. En el modo masa y velocidad también verás abajo el valor intermedio `p = m·v`.

### Botones de ejemplo (presets)

Debajo de los campos hay botones rápidos que cargan valores reales por vos:

| Botón | Qué carga |
|---|---|
| **Electrón** | masa y velocidad típicas de un electrón |
| **Protón** | masa y velocidad típicas de un protón |
| **Pelota de béisbol** | objeto cotidiano (0,145 kg a 40 m/s) |
| **Persona caminando** | 70 kg a 1,4 m/s |

Tocá cualquiera para ver al instante cómo una partícula diminuta tiene una onda apreciable mientras que un objeto cotidiano la tiene completamente despreciable.

---

## 4. Calculadora de Heisenberg (incertidumbre Δp)

Responde a la idea: *si fijás muy bien la posición de una partícula, su cantidad de movimiento se vuelve borrosa.* No es un problema de los instrumentos: es una propiedad de la naturaleza.

### Pasos

1. En el campo **"Incertidumbre en posición Δx"** escribí, en metros, qué tan bien conocés la posición. Cuanto más chico el número, más precisa es la posición.
2. Leé el resultado en el recuadro **"Incertidumbre mínima Δp"**.
3. Como referencia tangible, debajo verás esa incertidumbre traducida a **velocidad mínima si la partícula fuera un electrón** (Δv ≥ …).

### Botones de ejemplo (presets)

| Botón | Δx que carga |
|---|---|
| **Átomo (0.1 nm)** | 1 × 10⁻¹⁰ m |
| **Núcleo** | 1 × 10⁻¹⁴ m |
| **Célula** | 1 × 10⁻⁶ m |
| **Milímetro** | 1 × 10⁻³ m |

Probá pasar de "Milímetro" a "Núcleo" y vas a ver cómo la incertidumbre del momento se dispara cuando intentás encerrar la partícula en un espacio cada vez más chico.

---

## 5. Semáforo de escala (interpretación automática)

Esta sección **lee el resultado de la calculadora de De Broglie** y lo clasifica solo. No tenés que ingresar nada; cambia cada vez que modificás la calculadora de la izquierda.

Las tres luces significan:

- **Microscópica (verde)** — λ ≥ 0,1 nm. La onda es comparable o mayor al tamaño de átomos y moléculas. Los efectos cuánticos (difracción, interferencia) **se pueden observar**.
- **Mesoscópica (ámbar)** — zona de transición entre lo cuántico y lo clásico. La onda es diminuta pero todavía no del todo despreciable.
- **Macroscópica (roja)** — λ menor que ~1 femtómetro (más chica que un protón). La onda es despreciable y el objeto se comporta de forma **clásica**, como en la física de todos los días.

Debajo de las luces, un **texto explicativo** te dice en palabras qué pasa con tus valores, y una **barra horizontal** ubica tu longitud de onda (marcador "λ") respecto a tamaños de referencia: protón, átomo, virus, cabello y ser humano. La barra usa escala logarítmica para poder mostrar tamaños tan distintos en un mismo lugar.

---

## 6. Ver las fórmulas y la teoría

Cada calculadora tiene un **botón de información (ⓘ)** en la esquina superior derecha:

- Al **pasar el cursor** por encima aparece un resumen corto con la fórmula.
- Al **hacer clic** se abre una ventana con la explicación completa: el origen histórico, las fórmulas que usa la app, las variables y constantes, y cómo interpretar el resultado.
- Para cerrar la ventana podés usar el botón **Cerrar**, la **✕** de la esquina, hacer clic **fuera** del recuadro, o presionar la tecla **Esc**.

Las constantes que usa la app son oficiales (CODATA): constante de Planck h = 6,62607015 × 10⁻³⁴ J·s y ℏ = h/2π.

---

## 7. Ejemplos guiados

### Ejemplo A — ¿Por qué no vemos la onda de una pelota?

1. En la calculadora de De Broglie, tocá el preset **Pelota de béisbol**.
2. Observá la longitud de onda: es un número extraordinariamente pequeño.
3. Mirá el semáforo: se enciende la luz **Macroscópica (roja)**. Conclusión: la pelota es pura "partícula"; su onda no se nota.
4. Ahora tocá **Electrón**. La longitud de onda crece muchísimo y el semáforo pasa a **Microscópica (verde)**: ahí sí los efectos ondulatorios importan.

### Ejemplo B — El precio de conocer bien la posición

1. En la calculadora de Heisenberg, tocá **Milímetro** y anotá el valor de Δp.
2. Ahora tocá **Núcleo**.
3. Compará: al exigir muchísima más precisión en la posición, la incertidumbre del momento se vuelve enorme. Eso es el principio de Heisenberg en acción.

---

## 8. Problemas frecuentes

| Lo que ves | Causa probable | Solución |
|---|---|---|
| Aparece **—** en el resultado | Un campo está vacío, en cero o tiene texto inválido | Revisá que todos los campos tengan números válidos |
| El resultado no cambia | Quizás estás escribiendo en el modo equivocado | Verificá qué pestaña (Masa y velocidad / Cantidad de movimiento) está activa |
| El semáforo dice "Ingresá valores…" | La calculadora de De Broglie no tiene un resultado válido | Completá masa y velocidad, o el momento |
| La onda de fondo no se mueve | Tu dispositivo tiene activado "reducir movimiento" | Es intencional, por accesibilidad; no afecta los cálculos |

---

## 9. Requisitos y accesibilidad

- Funciona en cualquier navegador moderno (Chrome, Firefox, Safari, Edge) en computadora o celular.
- **No requiere conexión** para calcular, aunque sí usa internet para cargar las tipografías y los íconos.
- Es **navegable con teclado** (tabulador para moverse, Enter/Espacio para activar botones, Esc para cerrar ventanas) y respeta la preferencia del sistema de "reducir movimiento".

---

*Calculadora educativa de dualidad onda–partícula. Hecha con HTML, CSS y JavaScript. Constantes según CODATA.*
