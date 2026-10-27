# Tareas del equipo · AgendaVet

**Entrega a Alejandro:** miércoles 28 de octubre, 20h00 (así queda un día para subir todo antes de la tarea del jueves 29, 23:59).
**Cómo entregar:** llenen el CSV que les toca (se abre con Excel o Google Sheets) y mándenlo por WhatsApp o súbanlo a la carpeta `datos/` del repo.

Regla del profe: **nada inventado**. Cada dato lleva su fuente (link, nombre de la veterinaria o "encuesta"). Si no encuentran algo, escriban `NO ENCONTRADO`; no lo rellenen.

---

## Mensaje para el grupo (copiar y pegar)

> Panas, ya está la base de la presentación en el GitHub (presentacion/index.html). Faltan dos cosas y nos las dividimos:
>
> **[Compañero 1] → Competencia.** Buscar mínimo 5 competidores (chatbots de WhatsApp y software para veterinarias) y llenar `datos/competencia.csv`. Lo importante: precio, si es para veterinarias o no, y en qué somos mejores.
>
> **[Compañero 2] → Datos de viabilidad.** (a) Contar cuántas veterinarias hay en Quito, (b) hablar con mínimo 3 veterinarias, (c) hacer la encuesta de la tarea a mínimo 15 compañeros. Todo en `datos/mercado.csv`, `datos/entrevistas.csv` y el .csv de Google Forms.
>
> Pásenme todo hasta el **miércoles 28 a las 8 p. m.** Las instrucciones exactas están en `docs/TAREAS_EQUIPO.md`. Gracias 🙌

---

## Compañero 1 · Análisis de competencia

**Objetivo:** demostrar con datos la frase "hay competencia, pero no enfocada en clínicas" (lámina 8).

1. Buscar **mínimo 5** competidores en tres grupos:
   - **Chatbots / automatización de WhatsApp genéricos** (herramientas tipo plataforma de chatbot o bandeja compartida de WhatsApp Business).
   - **Software de gestión veterinaria** usado en Latinoamérica (agenda, historia clínica).
   - **Competencia local**: agencias o freelancers de Quito que venden bots de WhatsApp (buscar en Google, Facebook Marketplace, Instagram).
2. Para cada uno, llenar una fila de `datos/competencia.csv`:

| Columna | Qué poner | Ejemplo |
|---|---|---|
| nombre | Nombre del producto | — |
| tipo | `chatbot_generico`, `software_veterinario` o `local` | chatbot_generico |
| que_hace | Una frase | Bandeja compartida de WhatsApp con bot |
| precio_mensual_usd | Precio del plan más barato en USD | 49 |
| agenda_citas | si / no | si |
| enfocado_veterinarias | si / no | no |
| dashboard_estadisticas | si / no | no |
| cliente_configura_solo | si / no | si |
| debilidad | Por qué una veterinaria pequeña no lo usaría | Muy caro, en inglés |
| fuente | Link a la página de precios | https://… |

3. Al final, escribir **3 frases** en `datos/conclusion_competencia.txt`:
   - ¿Cuál es el competidor más peligroso y por qué?
   - ¿Quién es más barato que nosotros, si alguien lo es?
   - ¿Qué tenemos nosotros que ninguno tiene?

---

## Compañero 2 · Datos de viabilidad (mercado + campo + encuesta)

**Objetivo:** llenar los recuadros amarillos de las láminas 2, 5, 9 y 10, y cumplir la tarea del jueves 29.

### A. Tamaño del mercado → `datos/mercado.csv`
- ¿Cuántas clínicas veterinarias hay en Quito? Probar con: búsqueda "veterinaria" en Google Maps por sectores (norte, centro, sur, valles), catastro del SRI por actividad económica (atención veterinaria), directorios y gremios veterinarios.
- Anotar cada fuente con su número. No sumar fuentes que se repiten; quedarse con la más confiable y explicar por qué.
- ¿Cuánto gana una persona de atención/recepción en una veterinaria de Quito? (confirma o corrige nuestro "$800"). Fuente: ofertas de empleo o preguntando en las visitas.

### B. Visitas a veterinarias → `datos/entrevistas.csv`
Mínimo **3 veterinarias pequeñas o medianas**. Preguntar **por hechos pasados**, no por lo que harían:
1. La semana pasada, ¿cuántos mensajes de WhatsApp recibieron más o menos al día?
2. ¿Quién los contesta? ¿Cuántas horas al día se le van en eso?
3. ¿Cuánto le pagan a esa persona al mes (o qué parte de su sueldo es para eso)?
4. El último mes, ¿perdieron alguna cita o cliente por no contestar a tiempo o fuera de horario? ¿Cuántas?
5. ¿Usan algún programa o bot hoy? ¿Cuál y cuánto pagan?
6. Si les mostramos un bot que agenda solo, ¿lo probarían gratis 2 semanas? (Si dice sí: pedir nombre y número para el piloto → esto es nuestra evidencia de "viable").

Anotar **una frase textual** del dueño (la usamos en la lámina 2).

### C. Encuesta de la tarea (formato 6) → Google Forms
Mínimo **15 compañeros con mascota**, anónima (sin nombres, correos ni teléfonos):

| Filtro | Pregunta |
|---|---|
| Alcance | En las últimas 4 semanas, ¿escribiste por WhatsApp a una veterinaria? Sí / No |
| Frecuencia | ¿Cuántas veces le escribiste en esas 4 semanas? |
| Intensidad | La última vez, ¿cuánto te molestó lo que tardaron en responder? 1 (nada) a 5 (muchísimo) |
| Gasto actual | La última vez, ¿cuánto tiempo esperaste la respuesta? (menos de 10 min / 10–60 min / 1–5 h / más de 5 h / nunca respondieron) |
| Extra | ¿Alguna vez cambiaste de veterinaria porque no te respondieron? Sí / No |

Entregar: el **.csv original** que descarga Google Forms (sin editar) y los promedios de cada filtro.

---

## Lo que hace Alejandro con lo que le pasen
- Reemplaza todos los recuadros amarillos de `presentacion/index.html`.
- Actualiza el formato 6 y el formato 9 y los sube al aula virtual (jueves 29, 23:59).

## Cosas que el equipo tiene que decidir (no son datos, son decisiones)
- [ ] **Nombre** del producto (AgendaVet es provisional).
- [ ] **Precio del plan Pro**: en la hoja escribimos $13,99 y Alejandro dijo $10–$25. La presentación usa **$15**; confirmar.
- [ ] **Plan Empresa a $25 para 5+ sedes** sale más barato por sede que el Básico. ¿Es a propósito o debería ser por sede?
- [ ] **Costo por clínica** (API de WhatsApp + servidor + IA) para calcular el precio mínimo de la lámina 9.
