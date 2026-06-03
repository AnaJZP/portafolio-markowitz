#  Econometría Financiera

**Material educativo interactivo** para el curso de Econometría Financiera — desde la teoría clásica de Markowitz hasta Black-Litterman, métodos de optimización y backtesting.

> **Autora:** Ana Lorena Jiménez Preciado  
> **Institución:** Escuela Superior de Economía — Instituto Politécnico Nacional (ESE, IPN)

---

##  Contenido

| Sección | Tema | Descripción |
|:-------:|------|-------------|
| 01 | **¿Qué es la Diversificación?** | Riesgo sistemático vs. no sistemático, correlación y el efecto de diversificar. |
| 02 | **Formulación Media-Varianza** | El problema de optimización de Markowitz: rendimiento esperado, varianza del portafolio, y la función objetivo. |
| 03 | **Frontera Eficiente y CAPM** | Portafolio de mínima varianza, frontera eficiente, línea del mercado de capitales y el CAPM. |
| 04 | **Simulación Interactiva** | Simulación de 500 portafolios aleatorios con frontera eficiente, portafolio tangente y gráficos interactivos. |
| 05 | **Datos Reales BMV** | Descarga de precios de la Bolsa Mexicana de Valores, cálculo de rendimientos y optimización con datos reales. |
| 06 | **Variantes, Portafolio Dinámico y VaR** | 8 modelos alternativos a Markowitz (BL, Risk Parity, HRP, CVaR…), rebalanceo dinámico y simulador de VaR componente. |
| 07 | **Modelo Black-Litterman** | Intuición bayesiana, los 5 ingredientes (Π, P/q, Ω, τ, μ_BL), código Python completo y simulador interactivo. |
| 08 | **Calibración de τ y Forma Alternativa** | Equivalencia Woodbury/Kalman, no-identificabilidad τ/Ω, método de Idzorek y simuladores de mezcla prior↔view. |
| 09 | **Restricciones en Black-Litterman** | Restricciones sectoriales, tracking error vs benchmark, portafolios long-short — todo con CVXPY y simuladores. |
| 10 | **Métodos de Optimización** | Solver analítico (SLSQP) vs Simulación Monte Carlo. Comparación visual, ventajas/limitaciones y código Python. |
| 11 | **Backtesting y Evaluación** | Sharpe, Sortino, máximo drawdown, Calmar ratio, equity curve interactiva y framework completo de evaluación. |

---

##  Características

- **Interactivo:** Simuladores con sliders en tiempo real para ajustar parámetros y observar resultados al instante.
- **Gráficos dinámicos:** [Plotly.js](https://plotly.com/javascript/) y [Chart.js](https://www.chartjs.org/) para visualización interactiva con zoom, tooltips y comparaciones.
- **Ecuaciones renderizadas:** Formulación matemática rigurosa con [MathJax](https://www.mathjax.org/).
- **Código Python incluido:** Implementaciones completas con `numpy`, `scipy` y `cvxpy` — con botón de copiar integrado.
- **Syntax highlighting:** Bloques de código con [highlight.js](https://highlightjs.org/) para legibilidad.
- **Diseño responsivo:** Optimizado para desktop, tablet y dispositivos móviles con dark theme.
- **Sin dependencias de servidor:** Páginas estáticas listas para GitHub Pages, sin necesidad de backend.

---

##  Ver en línea

La página está disponible en GitHub Pages:

```
https://anajzp.github.io/portafolio-markowitz/
```

---

## 🛠️ Tecnologías

| Tecnología | Uso |
|------------|-----|
| HTML5 + CSS3 + JavaScript | Estructura, diseño y lógica |
| [MathJax 3](https://www.mathjax.org/) | Renderizado de ecuaciones LaTeX |
| [Plotly.js](https://plotly.com/javascript/) | Gráficos interactivos (frontera eficiente, scatter) |
| [Chart.js 4](https://www.chartjs.org/) | Gráficos de barras interactivos (BL, restricciones) |
| [highlight.js](https://highlightjs.org/) | Syntax highlighting para bloques de código Python |
| [Google Fonts](https://fonts.google.com/) | Tipografía (Inter, Playfair Display) |

---

## 📖 Uso local

Para visualizar el contenido localmente, simplemente abre `index.html` en cualquier navegador moderno. No requiere instalación de dependencias.

Alternativamente, puedes usar un servidor local:

```bash
# Python 3
python -m http.server 8080

# Luego abre http://localhost:8080 en tu navegador
```

---

##  Estructura del proyecto

```
portafolio-markowitz/
├── index.html                                    # Página principal (9 secciones)
├── portafolio_markowitz_variantes_var.html        # Fuente: Variantes y VaR
├── black_litterman_explicacion_python.html        # Fuente: Black-Litterman
├── black_litterman_tau_forma_alternativa.html     # Fuente: Calibración τ
├── bl_restricciones_sector_te_longshort.html      # Fuente: Restricciones BL
└── README.md
```

---

##  Licencia

Material educativo de uso académico.  
© Ana Lorena Jiménez Preciado — ESE, IPN.

---

<p align="center">
  <sub>⚡ Impulsado con <strong>Antigravity</strong> y <strong>Claude</strong></sub>
</p>
