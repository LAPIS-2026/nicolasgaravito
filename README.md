# Códigos para Práctico — Prof. Nicolás Garavito-Camargo (LAPIS 2026)

Repositorio de materiales y códigos para el práctico del Profesor Nicolás Garavito-Camargo (*Galactic mergers in our backyard: The Milky Way interaction with its more massive satellites, the LMC, and the SMC*) en la escuela de astrofísica **XII LAPIS 2026**.

## Proyecto

- **Título**: *Rewinding the orbits of Milky Way stellar halo tracers*
- Integración de órbitas de trazadores del halo estelar (estrellas, corrientes estelares, cúmulos globulares y galaxias satélite) en potenciales dependientes del tiempo de la Vía Láctea que incluyen el efecto de la LMC utilizando `Agama` y `nbody_streams`.

## Software y Estructura

- `LAPIS26/` — Submódulo con el fork de [jngaravitoc/LAPIS26](https://github.com/jngaravitoc/LAPIS26) en [`LAPIS-2026/LAPIS26`](https://github.com/LAPIS-2026/LAPIS26) ([guía de instalación detallada](./LAPIS26/INSTALL.md)).

## Lecturas Previas Sugeridas

- [Vasiliev et al. (2023) — The effect of the LMC on the Milky Way System](https://ui.adsabs.harvard.edu/abs/2023Galax..11...59V/abstract)
- [Garavito-Camargo et al. (2019) — Hunting for the Dark Matter Wake Induced by the LMC](https://ui.adsabs.harvard.edu/abs/2019ApJ...884...51G/abstract)
- [Patel et al. (2020) — The Orbital Histories of Magellanic Satellites Using Gaia DR2 Proper Motions](https://ui.adsabs.harvard.edu/abs/2020ApJ...893..121P/abstract)

## Cómo clonar este repositorio (incluyendo submódulos)

```bash
git clone --recurse-submodules https://github.com/LAPIS-2026/nicolasgaravito.git
```

Si ya clonaste el repositorio sin `--recurse-submodules`, inicializa y descarga todos los submódulos con:

```bash
git submodule update --init --recursive
```
