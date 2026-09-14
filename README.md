# sec-proy — Soluciones a retos de ciberseguridad

Este repositorio reúne, de forma incremental, las soluciones (writeups) a distintos retos y plataformas de ciberseguridad: CTFs, wargames y máquinas de hacking. Cada plataforma vive en su propia carpeta de nivel superior y se va incorporando al repo gradualmente conforme se retoma el trabajo en ella.

## Estado actual

Cada proyecto incluido es un **repositorio hijo**, referenciado aquí como submódulo git:

- **[`cylab-picoctf/`](https://github.com/hackadvisermx/cylab-picoctf)** — soluciones a retos de **picoCTF** alojados en [CyLab Security Academy](https://learn.cylabacademy.org), organizados por categoría y dificultad.
- **[`overthewire-bandit/`](https://github.com/hackadvisermx/overthewire-bandit)** — soluciones al wargame **Bandit** de OverTheWire.
- **[`overthewire-natas/`](https://github.com/hackadvisermx/overthewire-natas)** — soluciones al wargame **Natas** de OverTheWire.
- **[`hackmyvm-venus/`](https://github.com/hackadvisermx/hackmyvm-venus)** — soluciones al wargame **Venus** de HackMyVM.

### Contenido hasta el momento

- **cylab-picoctf**
  - General Skills — Easy: 48/48 retos resueltos y documentados.
  - General Skills — Medium: 8 retos resueltos y documentados (los que estaban pendientes en esta cuenta; algunos otros de esta subcategoría ya aparecían resueltos de antes y quedan pendientes de writeup).
  - Web Exploitation — Easy: 16/20 retos documentados (en curso, en bloques de 4).
- **overthewire-bandit**: 34/34 niveles (0-33) resueltos y documentados — completo.
- **overthewire-natas**: 35/35 niveles (0-34) resueltos y documentados — completo.
- **hackmyvm-venus**: cadena completa, 51/51 misiones (0x01-0x51) resueltas y documentadas — completo.

Cada reto/nivel tiene su propio writeup con la técnica usada para resolverlo (sin publicar flags ni contraseñas).

### Próximamente

- Resto de **Web Exploitation — Easy** (4 retos restantes) y el resto de categorías de picoCTF: Cryptography, Reverse Engineering, Forensics, Binary Exploitation, Blockchain, Artificial Intelligence.
- El resto de proyectos que ya existen localmente pero todavía no forman parte de este repo: `hackmyvm-hades`. Se irá agregando cuando se retome.
