# Hola, soy Carlos Castro Reales 👋

**Software Engineer · AI** · 🌐 [carlosed7641.github.io](https://carlosed7641.github.io)

Desarrollador con más de 4 años de experiencia, especializado en **frontend** con Angular, React y Next.js. He participado en el desarrollo de **portales de noticias y medios de alto tráfico** y de **plataformas e-commerce en VTEX** para marcas de varios países de Latinoamérica. Hoy me enfoco en construir **soluciones con IA**: RAG, búsqueda semántica y orquestación de agentes.

- 📰 Participé en rediseños de portales de TV, radio y deportes, y desarrollé módulos como señales en vivo, páginas de episodios con integración de video y experiencias interactivas.
- ⚡ Implementé lazy loading por secciones en portales de alto tráfico, logrando mejoras en **Core Web Vitals** y en tiempos de carga.
- 🛒 Participé en la evolución de tiendas VTEX con React y TypeScript: componentes reutilizables, landings de campaña y mejoras de experiencia de usuario.
- 🤖 Actualmente construyo apps con LLMs: RAG, búsqueda híbrida, tool calling y agentes.

## Stack

[![Stack](https://skillicons.dev/icons?i=ts,angular,react,nextjs,nodejs,tailwind)](https://skillicons.dev)

**IA:** RAG · Embeddings · Búsqueda vectorial e híbrida · Tool calling · Orquestación de agentes · Claude API

**Datos:** PostgreSQL + pgvector · SQLite + sqlite-vec · Supabase · Prisma

## Proyectos destacados

### [RagTech](https://github.com/carlosed7641/rag-ecommerce) · [Demo](https://rag-ecommerce-gilt.vercel.app)

E-commerce full-stack (tienda + CMS) con un asistente de compras que entiende lenguaje natural, desde *"algo cómodo para hacer ejercicio"* hasta *"productos de menos de 150.000 pesos"*.

- **Cómo:** Claude decide con tool calling si usar búsqueda semántica (pgvector), filtros estructurados o ambos.
- **Decisión clave:** el modelo nunca escribe SQL. Cada herramienta recibe parámetros tipados y validados con Zod, y el servidor arma la consulta, lo que evita inyecciones y fugas de datos.

`Next.js` `Supabase` `pgvector` `Claude API` `Voyage AI` `Zod`

### [Second Brain](https://github.com/carlosed7641/second-brain)

App local-first para guardar contratos, PDFs, recibos e imágenes escaneadas y hacerles preguntas en lenguaje natural, con respuestas que citan el documento y la página de origen.

- **Cómo:** búsqueda híbrida (vectores + full-text fusionados con RRF) y OCR para documentos escaneados.
- **Decisión clave:** un modelo ligero clasifica cada pregunta. Las de metadatos (*"¿cuándo vence mi seguro?"*) se responden con SQL directo, sin pasar por RAG, y el prompt caching mantiene bajo el costo en chats largos.

`Next.js` `SQLite` `sqlite-vec` `Claude API` `Tesseract.js`

### [Life Dashboard](https://github.com/carlosed7641/life-dashboard) · [Demo](https://life-dashboard-gamma-khaki.vercel.app)

Panel único con calendario, correos, tareas y notas conectado a las APIs de Google, con resumen diario y chat asistente con Claude.

`Next.js` `Auth.js` `Prisma` `Google APIs` `Claude API`

## Contacto

[![Portfolio](https://img.shields.io/badge/Portfolio-15803D?style=flat&logo=googlechrome&logoColor=white)](https://carlosed7641.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/carlos-castro-reales)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:carlosed7641@gmail.com)
