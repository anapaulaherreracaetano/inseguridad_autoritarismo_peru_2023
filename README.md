# Diccionario de datos
Análisis de la relación entre la percepción de inseguridad y las actitudes autoritarias en el Perú (2023), con base en datos de LAPOP.

| Tipo              | Variable (nombre en R)       | Descripción breve                                            |
| ----------------- | ---------------------------- | ------------------------------------------------------------ |
| **Independiente** | prioridad_seguridad (A4N)    | Problema principal del país (1 = Seguridad, 0 = Otro)        |
| **Dependiente** | apoyo_golpe (JC10/JC13)      | Justifica golpe militar por crimen/corrupción (1 = Sí, 0 = No)|
| **Dependiente** | apoyo_cierre (JC15A/JC16A)   | Justifica cierre de Congreso/Corte (1 = Sí, 0 = No)          |
| **Dependiente** | lider_fuerte (CSES6N)        | Apoyo a líder que rompe reglas (1 = Bajo ... 5 = Alto)       |
| **Dependiente** | limitar_oposicion (POP101)   | Apoyo a limitar voto opositor (1 = Bajo ... 7 = Alto)        |
| **Dependiente** | cinismo_democ (ING4)         | Rechazo a la democracia (1 = Bajo ... 7 = Alto)              |
| **Control** | victima_delito (VIC1EXT)     | Víctima de delito último año (1 = Sí, 0 = No)                |
| **Control** | percep_inseguridad (AOJ11)   | Inseguridad en el barrio (1 = Seguro ... 4 = Muy inseguro)   |
| **Control** | sexo_mujer (Q1TC)            | Sexo del encuestado (1 = Mujer, 0 = Hombre)                  |
| **Control** | educacion_anos (EDRE)        | Años de educación alcanzados (Numérico 0-18)                 |
| **Control** | ingresos_rango (Q10INC)      | Nivel de ingreso familiar mensual (Ordinal 1-16)             |
| **Geográfica** | PROV                         | Departamento/Provincia (para mapas)                          |
| **Geográfica** | ESTRATOPRI                   | Macro-región (Costa, Sierra, Selva)                          |
| **ID** | IDNUM                        | Identificador único del encuestado                           |
