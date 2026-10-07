# Renasté · plataforma (app.renaste.com)

Páginas de la plataforma de Clínicas Renasté, servidas por GitHub Pages en
**app.renaste.com**. Clonadas de la plataforma Zorvix el 7 oct 2026.

| Ruta | Módulo |
|---|---|
| `/` | Portal (lanzador) |
| `/cirugias/` | AltaRenasté: agenda de quirófanos y camas, alta de pacientes |
| `/ficha/` | Ficha que llena el paciente desde su liga |
| `/cirujanos/` | Credenciales de médicos |
| `/expediente/` | Expediente clínico electrónico |
| `/aviso/` | Aviso de privacidad — **BORRADOR, no vigente** |

Aquí no hay datos de pacientes ni código de servidor: eso vive en Apps Script
(cuenta clinicasrenastere@gmail.com) y en el repo privado `renaste-servidor`.

Pendiente: marca oficial de Renasté (la paleta y los logotipos de `assets/` son
provisionales) y los formatos impresos con membrete de Renasté (apagados con
`FORMATOS_IMPRESOS_LISTOS = false` en `expediente/index.html`).
