---
theme: jekyll-theme-orderedlist
title: Portafolio de Proyectos - Análisis de Datos

---
# Juan Castelblanco – Data Analyst Portfolio

---

<img width="1200" height="1600" alt="En el Trabajo" src="https://github.com/user-attachments/assets/566cb46b-f6fe-490f-8c62-316c7afc4901" />

---

![Data Analyst](https://img.shields.io/badge/Data_Analyst-Junior-brown?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-357ebd?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-357ebd?style=for-the-badge&logo=postgresql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-357ebd?style=for-the-badge&logo=powerbi&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-357ebd?style=for-the-badge&logo=tableau&logoColor=white)

---

## 👋 Acerca de mí

Llegué al análisis de datos desde el mundo clínico — y eso cambió cómo entiendo los problemas.

Soy Analista de Datos Junior con más de 8 años de experiencia en entornos regulados de salud y farmacéutica, donde gestioné bases de datos clínicas, automaticé reportes y comuniqué hallazgos a equipos directivos en entornos de alta exigencia. Hoy combino esa experiencia operativa con habilidades en Python, SQL, Power BI y Tableau para integrar datos de múltiples fuentes, construir dashboards ejecutivos y traducir hallazgos en decisiones de negocio concretas.

Me distingo por un enfoque metódico: planifico antes de ejecutar, documento cada decisión y entrego análisis claros, trazables y útiles para equipos técnicos y no técnicos.

### Habilidades técnicas

- Análisis y gestión de datos: **Python · SQL · Pandas · NumPy**
- Visualización: **Power BI · Tableau · Matplotlib · Seaborn**
- Metodologías: **CRISP-DM · Análisis de Cohortes · A/B Testing · EDA**
- Otras: **Limpieza y validación de datos · Dashboards ejecutivos · Documentación técnica**

### Habilidades blandas

Pensamiento analítico | Comunicación efectiva con equipos no técnicos | Orientación a resultados | Trabajo colaborativo | Atención al detalle | Organización y método | Resolución de problemas

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/juancastelblanco0126)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:juancastelblanco.da@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/juancast-data-analyst)

---

## 📂 Proyectos seleccionados

---

### 🔹 RappiPlus – Análisis integral de negocio

RappiPlus es un servicio de suscripción dentro del ecosistema de Rappi diseñado para aumentar la frecuencia de compra y el valor generado por usuario. El equipo de negocio necesitaba entender si el servicio estaba siendo rentable, dónde se perdían usuarios y si los cambios en el producto generaban impacto real.

#### Herramientas y tipo de proyecto

![Python](https://img.shields.io/badge/Python-357ebd?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-357ebd?style=for-the-badge&logo=pandas&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-357ebd?style=for-the-badge&logo=postgresql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-357ebd?style=for-the-badge&logo=powerbi&logoColor=white)
![Limpieza de datos](https://img.shields.io/badge/Limpieza_de_datos-295F98?style=for-the-badge)
![Análisis de Funnel](https://img.shields.io/badge/Análisis_de_Funnel-295F98?style=for-the-badge)
![Análisis de Cohortes](https://img.shields.io/badge/Análisis_de_Cohortes-295F98?style=for-the-badge)
![Test A/B](https://img.shields.io/badge/Test_A/B-295F98?style=for-the-badge)
![Dashboard ejecutivo](https://img.shields.io/badge/Dashboard_ejecutivo-295F98?style=for-the-badge)

#### Preguntas clave

1. ¿Podemos confiar en los datos? ¿Están limpios y listos para análisis?
2. ¿El negocio es rentable? ¿Dónde se generan pérdidas por producto?
3. ¿En qué etapa del proceso los usuarios dejan de comprar?
4. ¿Los usuarios regresan después de su primera compra?
5. ¿El cambio en la UI del checkout generó un impacto estadísticamente significativo?

#### Metodología

- **Calidad de datos:** Pipeline de limpieza reproducible sobre 25,100 órdenes integrando cinco fuentes de datos (pedidos, catálogo, marketing, eventos y experimento A/B)
- **Análisis de rentabilidad:** Cálculo de Revenue ($9,61M), Profit ($2,91M), Gasto en Marketing ($2,87M) y Ticket Promedio ($385,85) por producto, categoría y país
- **Funnel de conversión (SQL):** Análisis de 6 etapas (first_visit → purchase) con identificación del mayor punto de abandono
- **Cohortes de retención (SQL):** Construcción de matriz de retención semanal para evaluar comportamiento de usuarios en el tiempo
- **Test A/B estadístico (Python):** Z-test de proporciones para evaluar el impacto de un cambio de UI en el checkout
- **Dashboard ejecutivo (Power BI):** Dos vistas navegables — Overview Ejecutivo y Detalle/Drill-through por producto y país

#### Conclusiones y recomendaciones

- **Laptop-Gaming-16GB** genera el mayor volumen pero registra una pérdida de profit de -$417K; **Phone-Pro** y **Sneakers-Urban** son los productos más rentables
- El mayor drop-off del funnel ocurre entre `begin_checkout` y `add_payment_info` con una caída del **21,78%** — punto prioritario para optimización
- El test A/B concluyó que el cambio de UI **no generó mejora estadísticamente significativa** (p-value = 0,41); se recomienda mantener el diseño actual y explorar cambios en otras etapas del funnel
- Los tres mercados (México, Colombia, Argentina) presentan **revenue equilibrado**; el crecimiento futuro depende de estrategia, no de potencial de mercado

**Explora el repositorio completo →** [rappiplus-data-analysis](https://github.com/juancast-data-analyst/rappiplus-data-analysis)

---

### 🔹 Andes Capital Real Estate – Dashboard Comercial Inmobiliario

Empresa inmobiliaria con operaciones en Colombia y México que necesitaba una visión analítica clara de su desempeño comercial. La información existía a nivel transaccional pero no había una estructura que permitiera responder preguntas estratégicas sobre ventas, rentabilidad y recurrencia de clientes.

#### Herramientas y tipo de proyecto

![Power BI](https://img.shields.io/badge/Power_BI-357ebd?style=for-the-badge&logo=powerbi&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-357ebd?style=for-the-badge)
![Power Query](https://img.shields.io/badge/Power_Query-357ebd?style=for-the-badge)
![Esquema Estrella](https://img.shields.io/badge/Esquema_Estrella-295F98?style=for-the-badge)
![Inteligencia de Tiempo](https://img.shields.io/badge/Inteligencia_de_Tiempo-295F98?style=for-the-badge)
![Análisis de Cohortes](https://img.shields.io/badge/Análisis_de_Cohortes-295F98?style=for-the-badge)
![Dashboard ejecutivo](https://img.shields.io/badge/Dashboard_ejecutivo-295F98?style=for-the-badge)

#### Preguntas clave

1. ¿Cuál es el ingreso total y cómo ha evolucionado año contra año?
2. ¿Qué tipo de propiedad y canal de venta generan mayor rentabilidad?
3. ¿Los clientes vuelven a comprar después de su primera transacción?
4. ¿Qué segmentos de compradores aportan más valor al negocio?

#### Metodología

- **Modelado de datos:** Esquema estrella con tabla de hechos (`hecho_ventas_propiedades`) y tres dimensiones (`dim_clientes`, `dim_propiedades`, `dim_Fecha`) con relaciones 1:* y dirección de filtro simple
- **Tabla calendario dinámica:** Creada con DAX (`CALENDAR`, `ADDCOLUMNS`) para habilitar inteligencia de tiempo
- **Medidas DAX:** Ingreso Total, Ticket Promedio, Comisión Total, YoY, YTD, MTD y columnas calculadas de cohorte (`Cohorte`, `Mes Venta`, `Meses desde inicio`)
- **Dashboard (3 vistas):** Overview Ejecutivo con 5 KPIs, Análisis Comercial por tipo de propiedad y canal, y Análisis de Cohortes con matriz de retención e ingreso mensual

#### Conclusiones y recomendaciones

- El negocio generó **$6,012M en ingresos** con **8,500 ventas** y un crecimiento **YoY del 11,14%** sostenido durante 2023–2024
- **Departamento** lidera en volumen (5,105 unidades) pero tiene el ticket más bajo ($361K); **Comercial** tiene el menor volumen pero el mayor ticket ($1,797K) — oportunidad clara de optimización de mix de producto
- La retención promedio se estabiliza en **~9% por período**; los primeros dos períodos post-compra son la ventana crítica de intervención para mejorar recompra
- **Ciudad de México** concentra la mayor parte del ingreso por ciudad, seguida de Bogotá

**Explora el repositorio completo →** [andes-capital-real-estate](https://github.com/juancast-data-analyst/Dashboard-Analysis-and-Business-Strategy.)


## 🎯 Qué busco

Oportunidades remotas como **Data Analyst Junior** en empresas donde los datos generen impacto real — con preferencia en salud, farmacéutica, finanzas o e-commerce, y abierto a otros sectores donde pueda aportar valor desde el primer día.

---

## 📫 Contacto

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/juancastelblanco0126)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:juancastelblanco.da@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/juancast-data-analyst)
