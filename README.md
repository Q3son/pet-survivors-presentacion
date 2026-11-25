# Pet Survivors · Presentación

Presentación web del proyecto final **Veterinaria 2D / Pet Survivors** del curso
Tecnología de Objetos (UNSA, 1703240).

**En vivo:** https://pet-survivors-presentacion.vercel.app

**Código del juego:** https://github.com/sandra-aliaga/veterinaria-apocaliptica-to

## Contenido

18 diapositivas sobre el juego, la arquitectura MVC, la organización del código,
los patrones de diseño (Factory, Strategy, Command y Observer) y cómo se aplican
los temas del sílabo. Incluye diagramas UML de clases, estados y secuencia hechos
a partir de las cabeceras C++ del proyecto.

## Uso

- Flechas, espacio o Re Pág / Av Pág para cambiar de diapositiva.
- Clic en un diagrama para ampliarlo; Esc para cerrarlo.
- `presentacion_pet_survivors.html` es la versión de un solo archivo, con
  imágenes y fuentes incluidas, para abrirla sin conexión. Los diagramas UML se
  dibujan con [Mermaid](https://mermaid.js.org/) y sí necesitan internet.

## Desarrollo

Es un sitio estático sin dependencias de compilación:

```bash
python -m http.server 4173
```

y abrir http://localhost:4173.

## Créditos

- Equipo: Dai (consultorio), Mariana Yucra (mapa y misión), Edson Subia
  (catálogo y combate) y Sandra Aliaga (controlador, vista e integración).
- Arte pixel: Camila Alarico y Sandra Aliaga.
- Fuentes Pixelify Sans y Handjet bajo licencia SIL Open Font License
  (`assets/fuentes/`).
