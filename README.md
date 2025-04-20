# Algoritmos Fridrich Reducido - OLL y PLL

Este documento es una recopilación personal de los algoritmos del método Fridrich Reducido para resolver el Cubo de Rubik, centrado en las etapas OLL (Orientación de la Última Capa) y PLL (Permutación de la Última Capa).

## Notación de movimientos

Para consultar la notación usada en los algoritmos, puedes revisar estas imágenes:

- ![Notación 1](https://kubekings.com/img/cms/notacion-cubo/17.png)
- ![Notación 2](https://i.pinimg.com/736x/d3/ae/f7/d3aef7d30057cd83e9877e1a128767f1.jpg)

---

## 🟡 OLL (Orientación de la Última Capa)

### Caso: Pez (esquina al frente)
![img src="" width="250" style="transform: rotate(-90deg);"](https://myrubik.com/3x3x3/resolucio/fridrich/OLL/CR3_1024.webp)
```
R U2 R' U' R U' R'
```

### Caso: Pez (esquina contraria al frente)
![img src="" width="250"](https://myrubik.com/3x3x3/resolucio/fridrich/OLL/CR4_1024.webp)
```
R U R' U R U2 R'
```

### Caso: Cruz (esquinas alineadas)
![img src="" width="250"](https://myrubik.com/3x3x3/resolucio/fridrich/OLL/CR1_1024.webp)
```
R U2 R' U' [R U R' U'] R U' R'
```

### Caso: Cruz (esquinas desalineadas)
![img src="" width="250"](https://myrubik.com/3x3x3/resolucio/fridrich/OLL/CR2_1024.webp)
```
R U2 R2 U' R2 U' R2 U2 R
```

### Caso: Moño
![img src="" width="250" style="transform: rotate(180deg);"](https://myrubik.com/3x3x3/resolucio/fridrich/OLL/CR7_1024.webp)
```
L' U' L U' B U' L' U' L U B'
```

### Caso: Bloque de Lego (esquinas a los lados)
![img src="" width="250"](https://myrubik.com/3x3x3/resolucio/fridrich/OLL/CR6_1024.webp)
```
L F R' F' L' F R F'
```

### Caso: Bloque de Lego (esquinas al frente)
![img src="" width="250" style="transform: rotate(180deg);"](https://myrubik.com/3x3x3/resolucio/fridrich/OLL/CR5_1024.webp)
```
R U2 R' B' U R U R' U' B
```

---

## 🔁 PLL (Permutación de la Última Capa)

### Caso: No hay o solo una pareja de esquinas correctas
```
L' B L' F2 L B' L' F2 L2
```

### Caso: Permutación horaria de aristas (U-perm horario)
![img src="" width="250"](https://myrubik.com/3x3x3/resolucio/fridrich/PLL/complet/U2_1024.webp)
```
R' U R' U' R' U' R' U R U R2
```

### Caso: Permutación anti-horaria de aristas (U-perm antihorario)
![img src="" width="250"](https://myrubik.com/3x3x3/resolucio/fridrich/PLL/complet/U1_1024.webp)
```
R2 U' R' U' R U R U R U' R
```

### Caso: Aristas intercambiadas con su vecino (H-perm)
![img src="" width="250"](https://myrubik.com/3x3x3/resolucio/fridrich/PLL/complet/Z_1024.webp)
```
M2 U' M2 U' M' U2 M2 U2 M'
```

### Caso: Aristas intercambiadas con su opuesto en forma de cruz (Z-perm)
![img src="" width="250"](https://myrubik.com/3x3x3/resolucio/fridrich/PLL/complet/H_1024.webp)
```
M2 U M2 U2 M2 U M2
```

---

## 📌 Notas

- Revisa las imágenes de notación antes de practicar los algoritmos.
- La práctica constante y el reconocimiento de patrones visuales es clave para mejorar velocidad.
