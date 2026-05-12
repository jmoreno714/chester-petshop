# Contexto: Chester Pet Shop — Página de Información

## Objetivo
Crear una página de **información** (`/info` o similar) para Chester Pet Shop, basada en los datos de su tienda online en Pedix.

---

## Datos del negocio

| Campo | Valor |
|---|---|
| Nombre | Chester Pet Shop |
| Handle | `chesterpetshop` |
| Plataforma actual | [pedix.app/chesterpetshop](https://pedix.app/chesterpetshop) |
| Rubro | Pet shop — alimento balanceado para mascotas |
| Zona de cobertura | Yerba Buena, Tucumán, Argentina |
| Servicio | Delivery a domicilio |
| Instagram | [@Chesterpetshop_](https://instagram.com/Chesterpetshop_) |
| Logo | `https://cdn.pedix.app/W5wd6nR2wi2sRJWP8IXd/establishment-logo/logo-1771342104230.png` |
| Color de marca | `#21243d` (azul oscuro/marino) |

---

## Descripción del negocio (extraída del meta)

> "Hola! Somos Chester Pet Shop. Vendemos alimento balanceado con envío a domicilio en Yerba Buena. Calidad y comodidad para tu mascota sin moverte de casa."

---

## Categorías de productos disponibles

1. **Sieger / Agility** — Alimento marca Sieger/Agility
2. **Línea Vitalcan (Perros)** — Productos Vitalcan para perros
3. **Línea Vitalcan (Gatos)** — Productos Vitalcan para gatos
4. **EUKANUBA** — Alimentos premium Eukanuba
5. **Royal Canin** — Alimentos veterinarios Royal Canin
6. **Estampa** — Alimentos marca Estampa
7. **Camitas para Mascotas** — Accesorios / camas
8. **Fármacos** — Medicamentos/antiparasitarios
9. **Otros alimentos** — Marcas adicionales

---

## Navegación actual del sitio Pedix

- Inicio
- Información ← **(esta es la página a crear)**
- Ubicación
- Instagram

---

## Qué debe incluir la página `/info`

### Secciones sugeridas:

1. **Hero / Encabezado**
   - Logo de Chester Pet Shop
   - Nombre y slogan breve (ej: "Calidad y comodidad para tu mascota")

2. **Sobre nosotros**
   - Texto descriptivo del negocio
   - Zona de cobertura: Yerba Buena, Tucumán

3. **Qué ofrecemos**
   - Lista de categorías/marcas disponibles (ver sección arriba)
   - Íconos o cards por categoría

4. **Cómo comprarnos**
   - Proceso simple: elegir producto → pedir por WhatsApp/web → recibir en casa
   - Mencionar que tienen delivery a domicilio

5. **Contacto / Redes**
   - Link a Instagram: @Chesterpetshop_
   - Botón de WhatsApp (si se tiene el número, completar)
   - Zona de entrega: Yerba Buena

6. **Footer**
   - Logo, nombre, créditos

---

## Paleta de colores sugerida

| Rol | Color |
|---|---|
| Principal / fondo oscuro | `#21243d` |
| Acento cálido (mascotas) | `#f59e0b` o similar |
| Fondo claro | `#f9fafb` |
| Texto | `#1f2937` |

---

## Notas para Claude Code

- La página debe ser **HTML + CSS** estático (o React si se prefiere)
- Diseño **mobile-first** (la mayoría de usuarios acceden desde el celular)
- Usar el logo real desde la URL de CDN provista arriba
- El color `#21243d` es el color de marca principal
- Si falta información (como número de WhatsApp u horario), dejar un `<!-- TODO: completar -->` en el código
- El tono de la marca es **amigable, cercano y local**
