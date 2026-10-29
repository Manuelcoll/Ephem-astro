# efem-astro - Efemérides Completas para Astrología

### Rango de Tiempo

**Pack unificado a 1700-2126 (426 años)**
JD 2341972.5 a 2524600.5

- **de440.bsp (Planetas):** Original NASA 1550-2650, recortado a 1700-2126 para unificar.
- **Asteroides:** Rango nativo 1700-2126.

### Contenido Completo de bsp.zip

Este ZIP contiene TODO lo necesario para `engine.js`:

**1. Kernels Base:**
- `de440.bsp` - Sol, Luna, Mercurio, Venus, Tierra, Marte, Júpiter, Saturno, Urano, Neptuno, Plutón
- `naif0012.tls` - Leap seconds

**2. 11 Asteroides y Planetas Enanos (los más usados en astrología):**

| Astro | ID | Tipo | Tamaño aprox |
| :--- | :--- | :--- | :--- |
| **Ceres** | 2000001 | Planeta Enano | 7.32 MB |
| **Pallas** | 2000002 | Asteroide | |
| **Juno** | 2000003 | Asteroide | |
| **Vesta** | 2000004 | Asteroide | |
| **Chiron** | 2000206 | Centauro | 7.28 MB |
| **Hygiea** | 2000010 | Asteroide | |
| **Eris** | 200136199 | Planeta Enano | 7.28 MB |
| **Haumea** | 200136108 | Planeta Enano | |
| **Makemake** | 200136472 | Planeta Enano | |
| **Gonggong** | 200225088 | Planeta Enano | |
| **Sedna** | 20090377 | Sednoide | |

**Total: 13 archivos** dentro de `bsp.zip`

 - engine.js

> Usar `bsp.zip` completo desde:
> `https://github.com/Manuelcoll/efem-astro/releases/download/c1.0/bsp.zip`
> La función debe devolver longitud eclíptica de los 10 planetas + estos 11 asteroides.
