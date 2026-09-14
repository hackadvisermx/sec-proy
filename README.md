# sec-proy — Soluciones a retos de ciberseguridad

Este repositorio reúne, de forma incremental, las soluciones (writeups) a distintos retos y plataformas de ciberseguridad: CTFs, wargames y máquinas de hacking. Cada plataforma vive en su propia carpeta de nivel superior y se va incorporando al repo gradualmente conforme se retoma el trabajo en ella.

## Estado actual

Por ahora solo está incluido **[`cylab-picoctf/`](https://github.com/hackadvisermx/cylab-picoctf)** (repositorio hijo, referenciado como submódulo git), con las soluciones documentadas de los retos de **picoCTF** alojados en [CyLab Security Academy](https://learn.cylabacademy.org), organizados por categoría y dificultad.

### Contenido de `cylab-picoctf/` hasta el momento

- **General Skills — Easy**: 48/48 retos resueltos y documentados.
- **General Skills — Medium**: 8 retos resueltos y documentados (los que estaban pendientes en esta cuenta; algunos otros de esta subcategoría ya aparecían resueltos de antes y quedan pendientes de writeup).
- **Web Exploitation — Easy**: 4/24 retos documentados (en curso, en bloques de 4).

Cada reto tiene su propio writeup en `cylab-picoctf/challenges/<categoria>/{easy,medium}/<reto>/README.md`, documentando la técnica usada para resolverlo (sin publicar las flags).

### Próximamente

- Resto de **Web Exploitation — Easy** (20 retos restantes) y el resto de categorías de picoCTF: Cryptography, Reverse Engineering, Forensics, Binary Exploitation, Blockchain, Artificial Intelligence.
- El resto de proyectos que ya existen localmente pero todavía no forman parte de este repo: `hackmyvm-hades`, `hackmyvm-venus`, `overthewire-bandit`, `overthewire-natas`. Se irán agregando uno a uno.
