# RetailOps — Universidad Peruana de Ciencias Aplicadas (UPC)

> **Plataforma Integral de Analítica de Inventarios Retail, Optimización de Cadena de Frío y Mitigación de Mermas FEFO.**  
> Diseñado y desarrollado como solución de arquitectura de datos y sistemas de información en la Universidad Peruana de Ciencias Aplicadas (UPC), Lima, Perú.

[![Live Demo](https://img.shields.io/badge/Demo_en_Vivo-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://retail-inventory-web.vercel.app/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15_3NF-336791?style=for-the-badge&logo=postgresql&logoColor=white)](https://github.com/RetailOps-UPC/retail-inventory-analytics-3nf)
[![React](https://img.shields.io/badge/React-Vite_SPA-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://github.com/RetailOps-UPC/retail-inventory-web)

---

## 🏛️ Módulos de la Solución

| Módulo | Repositorio | Stack Tecnológico | Enlace Directo |
| :--- | :--- | :--- | :--- |
| **01. Operations Dashboard** | [`retail-inventory-web`](https://github.com/RetailOps-UPC/retail-inventory-web) | React 18, Vite, Tailwind CSS, Lucide | 🚀 [Ver Demo en Vivo](https://retail-inventory-web.vercel.app/) |
| **02. Data Engine & 3NF SQL** | [`retail-inventory-analytics-3nf`](https://github.com/RetailOps-UPC/retail-inventory-analytics-3nf) | PostgreSQL 15, Docker, Python ETL, PL/pgSQL | 🗄️ [Ver Arquitectura SQL](https://github.com/RetailOps-UPC/retail-inventory-analytics-3nf) |

---

## 🎯 Objetivos de Ingeniería & Negocio

1. **Mitigación Estructural de Mermas (FEFO):**
   * El 75.4% de las pérdidas operativas en retail de alta frecuencia proviene de productos caducados. RetailOps prioriza la salida de lotes mediante lógica determinista *First-Expired, First-Out*.
2. **Arquitectura Relacional Normalizada (3NF):**
   * 10 entidades relacionales libres de anomalías de inserción, actualización y borrado, con integridad referencial gobernada por triggers y procedimientos transaccionales en PostgreSQL.
3. **Auditoría de Recepciones vs. Guías (GRN):**
   * Control sistemático de discrepancias físicas entre lo facturado y lo recibido en tienda para prevenir sobrepagos a proveedores.

---

## 👨‍💻 Autor y Liderazgo Técnico

* **Odar Javier Alcocer Vásquez**  
  *Estudiante de Ingeniería de Sistemas de Información — Universidad Peruana de Ciencias Aplicadas (UPC)*  
  🌐 [Portafolio Oficial](https://odaralcocer.pages.dev) · 💻 [GitHub Profile (@MrOdar)](https://github.com/MrOdar)
