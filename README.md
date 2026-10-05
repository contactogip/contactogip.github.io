# Informes GIP

Portada de los informes ejecutivos mensuales de inspección técnica de obra de GIP, publicada en https://informes.gip.cl

| Obra | Dirección | Repositorio |
|------|-----------|-------------|
| Edificio Carrera (GIP_228) | https://informes.gip.cl/carrera/ | `contactogip/carrera` |
| Edificio Torre 1, Lote 18 (GIP_308) | https://informes.gip.cl/torre-1/ | `contactogip/torre-1` |
| Edificio HC2, Ampliación Clínica U Andes (GIP_267) | https://informes.gip.cl/Clinica-UAndes/ | `contactogip/Clinica-UAndes` |

- `index.html`: portada con una tarjeta por obra (foto, último informe y avance). Al emitir un informe nuevo se actualizan su número, período y avance.
- `CNAME`: dominio personalizado `informes.gip.cl` (registro CNAME `informes` → `contactogip.github.io` en el DNS de gip.cl, administrado en Wix).
- `media/`: logos de GIP y foto de cada obra.

Cada obra vive en su propio repositorio con GitHub Pages activo; al tener esta portada un dominio personalizado, cada obra queda disponible en `informes.gip.cl/<repositorio>/`.
