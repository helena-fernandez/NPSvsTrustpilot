# NPS vs Trustpilot · Dashboard — seQura · Abril 2026

Análisis comparativo entre las valoraciones internas (NPS) y las reviews públicas (Trustpilot) recibidas en abril de 2026, con el objetivo de entender qué plataforma está funcionando mejor para captar valoraciones y cómo aumentar las reviews positivas en Trustpilot.

> Dashboard interactivo en una sola página HTML, sin dependencias de build. Se renderiza directamente en el navegador.

---

## 🚀 Ver el dashboard

Una vez subido a GitHub y activadas las GitHub Pages, estará disponible en:

```
https://<tu-usuario>.github.io/<nombre-del-repo>/
```

También se puede abrir el `index.html` localmente haciendo doble clic.

### Activar GitHub Pages

1. Sube los archivos al repositorio.
2. Ve a **Settings → Pages**.
3. En *Source*, selecciona **Deploy from a branch** → rama `main` (o `master`) → carpeta `/ (root)`.
4. Guarda. En 1-2 minutos GitHub te dará la URL pública.

---

## 📊 Hallazgos clave

| Métrica | NPS | Trustpilot |
|---|---|---|
| Volumen abril 2026 | **3.575** valoraciones | **56** reviews |
| Puntuación media | ≈ **4,5 / 5** | **3,5 / 5** |
| % promotores | **89,1%** | — |

- El NPS recoge **64 veces más feedback** que Trustpilot.
- Las puntuaciones se contradicen: en NPS los usuarios nos puntúan excelente, en Trustpilot mal. La experiencia real es buena, la imagen pública no.
- **3.185 promotores (NPS 9-10)** que hoy no llegan a Trustpilot. Activar incluso un 10% multiplicaría las reviews por 6-7.

---

## 🗂️ Estructura del análisis

El dashboard está organizado en 6 bloques:

1. **Resumen general** — KPIs principales y evolución diaria.
2. **Volumen NPS vs Trustpilot** — comparativa por producto.
3. **Puntuación** — el contraste entre lo que nos dicen los usuarios en privado y en público.
4. **Distribución NPS** — promotores / pasivos / detractores.
5. **Tiendas en riesgo** — listas negras de Invoice y Pago Fraccionado para no enviar emails de Trustpilot.
6. **Oportunidad** — simulación del impacto de activar promotores.

Cierra con **Conclusiones** y **Next Steps** accionables.

---

## 🛠️ Stack

- HTML + CSS (sin frameworks, sin build).
- [Chart.js 4](https://www.chartjs.org/) cargado vía CDN para el gráfico de líneas y el donut.
- Tipografía [Inter](https://fonts.google.com/specimen/Inter) vía Google Fonts.
- Paleta de colores: verde teal seQura (`#00C2A3`, `#21CFAC`) + morado campaign (`#8B5CF6`) + acentos.

---

## 📁 Archivos

```
.
├── index.html     # Dashboard (todo el HTML, CSS y JS en un solo archivo)
└── README.md
```

---

## 📝 Datos

Las valoraciones provienen de tres pestañas internas:
- **Invoice — NPS**: 264 valoraciones (escala 0-10).
- **Pago fraccionado — NPS**: 3.311 valoraciones (escala 0-10).
- **Trustpilot — Reviews**: 56 reviews (escala 1-5).

Periodo: del 1 al 28 de abril de 2026.
