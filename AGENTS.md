# Reglas del Proyecto y Contexto: El Sazón del Valle (POS & Menú Digital)

## 📌 Descripción General

Sistema web ligero para el restaurante "El Sazón del Valle", compuesto por un menú público para clientes y un Punto de Venta (POS) interactivo para la caja. Desplegado en Cloudflare Pages mediante GitHub.

## 📁 Arquitectura de Archivos

- `index.html`: Vista pública del menú digital para clientes (QR/Móvil). Diseñado para lectura clara por categorías.
- `pos.html`: Sistema Punto de Venta interactivo para el cajero (buscador, carrito de compras, ajuste de cantidades, cobro en efectivo/tarjeta).
- `AGENTS.md`: Guía de contexto y reglas de negocio para los agentes de desarrollo.

## 🛠️ Stack Tecnológico

- **HTML5 & CSS:** Tailwind CSS (vía CDN).
- **JavaScript:** Vanilla JS sin frameworks ni compiladores.
- **Persistencia:** `localStorage` para almacenamiento local en el navegador.
- **Hosting:** Cloudflare Pages (sincronizado con la rama `main` en GitHub).

## 🌮 Catálogo Oficial de Productos y Precios (Única Fuente de Verdad)

### Chilaquiles (Rojos y Verdes)

- Sencillos: $55.00
- Con Huevo: $60.00
- Con Pollo: $65.00
- Con Bistec: $75.00

### Sándwiches

- Jamón: $30.00
- Salchicha: $35.00
- Pechuga Asada: $40.00
- Pechuga Empanizada: $45.00

### Tortas

- Jamón / Huevo: $30.00
- Salchicha / Pechuga / Pierna: $40.00
- Pechuga Empanizada: $45.00

### Ensaladas Nutritivas

Incluyen Pechuga Asada + Aderezo a elegir: Chipotle, Ranch, Finas Hierbas, Mil Islas, César.

- Ensalada Valle (lechuga, jitomate, zanahoria, aguacate, huevo cocido, crotones, cacahuate, queso panela): $80.00
- Ensalada Amor (lechuga, nuez, cacahuate, arándanos, queso panela, miel): $80.00

### Tacos

Acompañados con papas a la francesa y nopales.

- Taco de Bistec: $30.00
- Taco de Pechuga: $30.00

### Burritos

- Jamón con Queso: $60.00
- Pechuga: $70.00
- Bistec con Queso: $80.00

### Antojitos y Platillos

- Banderilla de Salchicha: $25.00
- Hotcake: $15.00 c/u
- Molletes (jamón, queso manchego, frijoles): $45.00
- Tacos Dorados: $60.00
- Enchiladas Suizas: $80.00
- Pechuga Asada (platillo): $80.00
- Pechuga Empanizada (platillo): $85.00

### Bebidas

- Café de Olla (endulzado con piloncillo): Chico $15.00 / Grande $20.00
- Café con Leche o Crema: Chico $15.00 / Grande $20.00
- Té Manzanilla: Chico $10.00 / Grande $15.00
- Té Limón: Chico $10.00 / Grande $15.00

## ⚠️ Reglas Indispensables para Agentes

- No alterar ni modificar los precios ni nombres oficiales del menú sin autorización explícita.
- Toda actualización de productos debe reflejarse en AMBOS archivos: `index.html` y `pos.html`.
- Mantener el diseño limpio usando las clases de Tailwind CSS preexistentes.
