# Diccionario de datos
Análisis de la relación entre la percepción de inseguridad y las actitudes autoritarias en el Perú (2023), con base en datos de LAPOP.


| Tipo | Variable (nombre en R) | Descripción breve |
| :--- | :--- | :--- |
| **Independiente** | **prioriza_seguridad** (A4N) | Problema principal del país (1 = Seguridad, 0 = Otro) |
| **Dependiente** | **actitud_golpe** (JC10/JC13) | Justifica golpe militar por crimen/corrupción (1 = Sí, 0 = No) |
| **Dependiente** | **actitud_cierre** (JC15A/JC16A) | Justifica cierre de Congreso o Corte (1 = Sí, 0 = No) |
| **Dependiente** | **actitud_lider** (CSES6N) | Preferencia por líder fuerte que rompe reglas (1–5) |
| **Dependiente** | **actitud_oposicion** (POP101) | Apoyo a que el ejecutivo limite a la oposición (1–7) |
| **Dependiente** | **actitud_cinismo** (ING4) | Rechazo a la democracia como mejor sistema (1–7) |
| **Control** | **victima_crimen** (VIC1EXT) | Víctima de un delito en los últimos 12 meses (1 = Sí, 0 = No) |
| **Control** | **miedo_barrio** (AOJ11) | Sensación de inseguridad en el barrio (1 = Seguro ... 4 = Inseguro) |
| **Control** | **confianza_policia** (B18) | Nivel de confianza en la Policía Nacional (1–7) |
| **Control** | **mujer** (Q1TC) | Sexo del entrevistado (1 = Mujer, 0 = Hombre) |
| **Control** | **educacion** (EDRE) | Nivel educativo alcanzado (Años acumulados 0–18) |
| **Control** | **ingresos** (Q10INC) | Nivel de ingreso familiar mensual (Escala 1–16) |
| **Geográfica** | **region_macro** (ESTRATOPRI) | Región natural (Costa, Sierra, Selva) |
| **Geográfica** | **departamento** (PROV) | Nombre del Departamento/Provincia |
| **ID** | **id** (IDNUM) | Identificador único del encuestado |
