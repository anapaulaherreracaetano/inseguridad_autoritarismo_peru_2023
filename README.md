# Diccionario de datos
Análisis de la relación entre la percepción de inseguridad y las actitudes autoritarias en el Perú (2023), con base en datos de LAPOP.

| Tipo              | Variable (nombre en R)            | Descripción breve                                            |
| ----------------- | --------------------------------- | ------------------------------------------------------------ |
| **Dependiente**   | A4N (problema)                    | Problema principal del país (1 = Seguridad, 0 = otro)       |
| **Independiente** | JC13 (autoritarismo_corrupcion)   | Justifica golpe de Estado ante corrupción (1 = sí, 0 = no)   |
| **Independiente** | JC10 (autoritarismo_delincuencia) | Justifica golpe de Estado ante delincuencia (1 = sí, 0 = no) |
| **Independiente** | JC15A (cierre_congreso)           | Justifica cierre del Congreso (1 = sí, 0 = no)               |
| **Independiente** | ING4 (democracia)                 | Nivel de acuerdo con la democracia (1–7)                     |
| **Independiente** | B18 (confianza_policia)           | Confianza en la Policía Nacional (1–7)                       |
| **Control**       | EDRE (educacion)                  | Nivel educativo (1 = primaria, 2 = secundaria, 3 = superior) |
| **Control**       | AOJ11 (inseguridad_barrio)        | Percepción de inseguridad en el barrio (1–4)                 |
| **Control**       | SEXIN (sexo)                      | 1 = hombre, 0 = mujer                                        |
| **Control**       | Q10INC (ingreso)                  | Nivel de ingreso familiar mensual                            |
| **Control** | `region` | Región natural del Perú según estrato muestral LAPOP (Costa, Sierra, Selva) |
