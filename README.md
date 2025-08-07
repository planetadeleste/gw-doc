# Documentación del Plugin PlanetaDelEste.GW

Esta carpeta contiene la documentación completa del plugin **PlanetaDelEste.GW**, un sistema integral de gestión empresarial para OctoberCMS.

## Estructura de la Documentación

```
storage/doc/
├── index.mdx                    # Página principal
├── instalacion.mdx             # Guía de instalación
├── configuracion-inicial.mdx   # Configuración inicial
├── mint.json                   # Configuración de Mintlify
├── modelos/                    # Documentación de modelos
│   ├── index.mdx
│   ├── facturacion/
│   │   ├── invoice.mdx
│   │   └── invoice-position.mdx
│   ├── contabilidad/
│   ├── clientes/
│   └── configuracion/
├── controladores/              # Documentación de controladores
│   └── index.mdx
├── componentes/               # Documentación de componentes
│   └── index.mdx
├── comandos/                  # Documentación de comandos Artisan
│   ├── index.mdx
│   └── saldos/
│       └── update-balance.mdx
├── api/                       # Documentación de la API REST
│   └── index.mdx
└── configuracion/             # Documentación de configuración
    └── index.mdx
```

## Uso con Mintlify

Esta documentación está optimizada para ser usada con [Mintlify](https://mintlify.com/), una plataforma moderna de documentación.

### Instalación Local de Mintlify

```bash
npm i -g mintlify

# Servir documentación localmente
cd storage/doc
mintlify dev
```

### Deployment

```bash
# Build para producción
mintlify build

# Deploy automático (configurar en Mintlify dashboard)
git push origin main
```

## Características

- ✅ **Formato MDX**: Soporte completo para React components
- ✅ **Componentes Interactivos**: Cards, Tabs, Accordions, etc.
- ✅ **Código Syntax Highlighting**: Múltiples lenguajes
- ✅ **Búsqueda Avanzada**: Búsqueda full-text integrada
- ✅ **Navegación Intuitiva**: Estructura jerárquica clara
- ✅ **Responsive**: Optimizado para móviles y desktop
- ✅ **Dark Mode**: Tema oscuro automático
- ✅ **Analytics**: Integración con Google Analytics

## Secciones Principales

### 📖 Introducción
- Información general del plugin
- Características principales
- Arquitectura del sistema

### ⚙️ Instalación y Configuración
- Requisitos del sistema
- Proceso de instalación paso a paso
- Configuración inicial completa

### 🗃️ Modelos de Datos
- Documentación completa de todos los modelos
- Relaciones entre entidades
- Ejemplos de uso prácticos

### 🎮 Controladores
- Controladores del backend
- Configuraciones YAML
- Personalización avanzada

### 💻 Comandos de Consola
- Comandos Artisan disponibles
- Parámetros y opciones
- Ejemplos de ejecución

### 🔌 API REST
- Endpoints disponibles
- Autenticación JWT
- Ejemplos de integración

### ⚡ Configuración Avanzada
- Variables de entorno
- Optimización de performance
- Configuración multi-empresa

## Contribuir a la Documentación

### Estructura de Archivos MDX

```mdx
---
title: "Título de la Página"
description: "Descripción breve para SEO"
---

# Título Principal

Contenido en Markdown con componentes MDX.

<CardGroup cols={2}>
  <Card title="Ejemplo" icon="star">
    Contenido de la tarjeta
  </Card>
</CardGroup>
```

### Componentes Disponibles

#### Cards
```mdx
<Card title="Título" icon="icon-name" href="/link">
  Contenido de la tarjeta
</Card>

<CardGroup cols={2}>
  <Card title="Card 1">Contenido 1</Card>
  <Card title="Card 2">Contenido 2</Card>
</CardGroup>
```

#### Tabs
```mdx
<Tabs>
  <Tab title="PHP">
    ```php
    // Código PHP
    ```
  </Tab>
  <Tab title="JavaScript">
    ```javascript
    // Código JavaScript
    ```
  </Tab>
</Tabs>
```

#### Alerts
```mdx
<Tip>
Consejo útil para los usuarios.
</Tip>

<Warning>
Advertencia importante.
</Warning>

<Info>
Información adicional.
</Info>
```

#### Steps
```mdx
<Steps>
  <Step title="Paso 1">
    Descripción del primer paso
  </Step>
  <Step title="Paso 2">
    Descripción del segundo paso
  </Step>
</Steps>
```

#### Accordion
```mdx
<Accordion>
  <AccordionItem title="Sección 1">
    Contenido expandible
  </AccordionItem>
  <AccordionItem title="Sección 2">
    Más contenido
  </AccordionItem>
</Accordion>
```

### Guidelines de Escritura

1. **Títulos**: Usar formato jerárquico (H1 > H2 > H3)
2. **Código**: Siempre especificar el lenguaje
3. **Enlaces**: Usar paths relativos para enlaces internos
4. **Imágenes**: Almacenar en carpeta `/images`
5. **Ejemplos**: Incluir ejemplos prácticos y funcionales

### Testing Local

```bash
# Verificar sintaxis
mintlify check

# Preview local
mintlify dev

# Build test
mintlify build
```

## Mantenimiento

### Actualizar Documentación

1. Modificar archivos MDX correspondientes
2. Verificar con `mintlify check`
3. Test local con `mintlify dev`
4. Commit y push para deploy automático

### Agregar Nueva Sección

1. Crear archivo MDX en carpeta apropiada
2. Actualizar `mint.json` en sección `navigation`
3. Agregar enlaces desde páginas relacionadas

### SEO y Performance

- Títulos y descripciones optimizadas
- Estructura semántica correcta
- Imágenes optimizadas
- Links internos consistentes

## Soporte

Para preguntas sobre la documentación:
- 📧 Email: docs@planetadeleste.com
- 💬 Slack: #documentacion
- 🐛 Issues: GitHub Repository

---

**Última actualización**: Enero 2025
**Versión del Plugin**: 1.0.0
**Formato**: Mintlify MDX
