# 🔐 Login Performance Test with K6

Este repositorio contiene una prueba de carga automatizada al endpoint de autenticación de la API pública [FakeStoreAPI](https://fakestoreapi.com/auth/login), utilizando la herramienta [K6](https://k6.io/).

El objetivo principal es evaluar el comportamiento del endpoint bajo condiciones de **concurrencia moderada**, validando:

- ⏱️ Tiempos de respuesta
- 📈 Estabilidad general
- ❌ Tasa de errores

---

## ⚙️ Requisitos

- ✅ [K6](https://k6.io/) v1.1.0 o superior
- 🧰 Sistema operativo: Windows, Linux o macOS
- 🌐 Conexión a internet activa

---

## 📁 Estructura del proyecto

```
k6-login-test/
├── data/
│   └── users.csv
├── scripts/
│   └── login_test.js
├── InformeResultados.docs  # Resumen técnico de la ejecución
├── textSummary.txt         # Resultados de la ejecución
├── conclusiones.txt        # Análisis técnico del ejercicio
├── readme.txt              # Instrucciones y guía de uso
└── README.md

```
