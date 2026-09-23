# Ecosistema de Automatización IA – Wineem

**Entrega Final – Curso de Automatización e Inteligencia Artificial**  
**Alumna:** Daniela Sorsini

## Descripción

Proyecto de automatización para la generación, revisión y publicación de contenido comercial de Wineem.

El ecosistema utiliza **n8n** como orquestador, **Airtable** como base de datos y memoria, **OpenAI** para la generación de contenido y **Gmail** como canal de notificación y envío.

El proceso incorpora una instancia de aprobación humana (**Human-in-the-Loop**) antes de la publicación final y mecanismos de registro y manejo de errores.

## Workflows

- **Workflow A:** generación de contenido utilizando Idea Semilla + Base RAG + OpenAI.
- **Workflow B:** aprobación humana y envío del contenido aprobado.
- **Workflow C:** detección y registro de errores de los workflows principales.

## Archivos incluidos

- `DIAGRAMA TP FINAL.pdf` – Diagrama de arquitectura.
- `ENTREGA FINAL SORSINI DANIELA.pdf` – Documentación completa y evidencias.
- `Proyecto Final - Workflow A` – Generación de contenido.
- `Proyecto Final - Workflow B` – Aprobación y envío.
- `Proyecto Final - Workflow C` – Manejo de errores.
- `Wineem_Ecosistema_IA_Final_comprimido.mp4` – Video demostrativo del funcionamiento del ecosistema.

## Tecnologías utilizadas

n8n · Airtable · OpenAI · Gmail

## Enlaces

- [Base de datos Airtable – acceso de solo lectura](https://airtable.com/appV6GlB8dBVZTVV6/shr1fjU4elD1e4ssA)
- [Dashboard de Control IA Wineem](https://airtable.com/appV6GlB8dBVZTVV6/pagPQWW0SCRpHXOfu)
