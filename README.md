# FinTech Colombia Dashboard — Colombia 5.0

Dashboard interactivo unificado para los Talleres 1 y 2 del programa Colombia 5.0 — MinTic / Universidad Distrital · Manizales 2026.

## Contenido del Dashboard

### Taller 1 — FinTech Colombia
- **KPIs animados**: 5 metricas clave con animacion GSAP (95.9% bancarizacion, 394 FinTechs, 22M Nequi...)
- **Crecimiento ecosistema**: Empresas FinTech 2017-2024 (barras + linea crecimiento %)
- **Donut segmentos**: Distribucion por vertical FinTech
- **Inversion VC**: Filtros interactivos Colombia / Brasil / Mexico
- **Billeteras digitales**: Rankings animados + evolucion Nequi vs Daviplata
- **Transacciones**: Volumen y operaciones 2019-2023
- **Linea de tiempo**: 1992-2025 interactiva con click para detalles
- **Bancarizacion**: Evolucion 2019-2024
- **Brecha de informalidad**: Datos especificos de Caldas
- **Remesas**: $9.8B USD anuales

### Taller 2 — DIAN, Neobancos & Blockchain
- **Facturacion electronica DIAN**: Crecimiento 2019-2024
- **Software contable**: Comparativa Wave, Alegra, GnuCash, ERPNext, Siigo
- **Neobancos Colombia**: LuloBank, Pibank, Movii, Rappipay, Uala
- **Rutas de microcredito**: ADDI, Juancho Te Presta, Mercado Credito, Bancamia
- **FinTech LATAM**: Top 5 paises por empresas FinTech
- **Bitcoin historico**: Precio 2020-2024
- **Blockchain explicado**: Flujo de 6 pasos visual
- **Estafas cripto**: Ponzi vs legitimo, caso OneCoin
- **DeFi & Open Finance**: Open Banking, DeFi, Wallets

## Stack

- HTML5 + CSS3 (sin framework)
- Chart.js 4.4 (graficos interactivos)
- GSAP 3.12 + ScrollTrigger (animaciones y scroll)
- Google Fonts: DM Sans + Space Mono + DM Serif Display
- Single-file: 0 dependencias npm, 0 build step

## Mejoras vs version anterior

- Menu hamburguesa responsive para movil
- Animaciones GSAP en KPIs (conteo numerico)
- ScrollTrigger para animaciones al hacer scroll
- Taller 2 completo integrado (DIAN, Blockchain, Cripto)
- Tabs para alternar entre Taller 1 y Taller 2
- Boton "volver arriba" flotante
- Navegacion con estado activo segun scroll
- Carga lazy de graficos del Taller 2
- Cards con animaciones de entrada
- Seccion de estafas cripto con alertas visuales

## Deploy en Vercel

```bash
cd fintech-dashboard
npx vercel --prod
```

## Uso Local

```bash
python3 -m http.server 8080
# o
npx serve .
```

Abre: http://localhost:8080

## Fuentes de Datos

- MinTic — Programa Colombia 5.0
- Universidad Distrital Francisco Jose de Caldas
- Colombia FinTech — Snapshot 2024
- Valora Analitik — Nequi cierre 2024
- Banco de la Republica — Remesas 2023
- CoinMarketCap — Datos historicos BTC
- DIAN — Facturacion electronica 2024
- GSMA Mobile Money 2024 — LATAM data
