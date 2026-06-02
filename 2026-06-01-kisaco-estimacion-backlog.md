# Kisaco Research — Estimación de Backlog
**Metodología:** Story points por historia (P50 = estimación esperada, P90 = con margen de riesgo).  
**Total de equipo aplicado:** RSS — el P90 total no es la suma de P90 individuales sino `Σ P50 + √(Σ (P90−P50)²)`, que refleja la independencia estadística de las historias.  
**Velocity asumida:** 15–20 pts/sprint (sprints de 2 semanas).

---

## Stage 2A — Lean (Responsive Web App)

### Epic 1: Sponsor Matchmaking
| Historia | P50 | P90 |
|---|---|---|
| Como sponsor, configuro mis criterios ICP para que la plataforma recomiende los attendees más relevantes | 5 | 8 |
| Como sponsor, envío invitaciones de reunión directamente a attendees matcheados desde la plataforma | 5 | 8 |
| Como sponsor, veo scores de calidad de match para priorizar outreach | 3 | 5 |
| **Subtotal** | **13** | **18** |

### Epic 2: Calendar Integration
| Historia | P50 | P90 |
|---|---|---|
| Como attendee, acepto o rechazo invitaciones de reunión sincronizadas con mi Google o Outlook | 5 | 8 |
| Como sponsor, veo las reuniones confirmadas reflejadas en mi calendario en tiempo real | 5 | 8 |
| Como participante, recibo recordatorios automáticos con confirmación de un toque | 3 | 5 |
| **Subtotal** | **13** | **18** |

### Epic 3: Personalized Journeys (3 a 5 categorías)
| Historia | P50 | P90 |
|---|---|---|
| Como sponsor, veo una pantalla de inicio con mi lista de matches, agenda de reuniones e ítems de acción | 5 | 8 |
| Como operador de health club, navego un journey diseñado para mi contexto de compra y objetivos | 8 | 13 |
| Como attendee, descubro sesiones y contactos relevantes según mi categoría de stakeholder | 5 | 8 |
| Como attendee, navego perfiles de sponsors y attendees y solicito reuniones con quienes me son relevantes | 5 | 8 |
| **Subtotal** | **21** | **29** |

### Epic 4: Show-up Tracking
| Historia | P50 | P90 |
|---|---|---|
| Como sponsor, veo el estado de confirmación en tiempo real de cada attendee invitado | 3 | 5 |
| Como equipo Kisaco, monitoreo tasas de show-up por sponsor para identificar reuniones en riesgo | 3 | 5 |
| Como attendee, recibo un recordatorio de reunión con ubicación clara y detalles de acceso | 3 | 5 |
| **Subtotal** | **8** | **13** |

### Epic 5: Attendee Profile
| Historia | P50 | P90 |
|---|---|---|
| Como attendee, completo mi perfil con rol, empresa y objetivos para aparecer en matches de sponsors | 3 | 5 |
| Como attendee, califico una reunión completada para que la plataforma mejore recomendaciones futuras | 2 | 3 |
| **Subtotal** | **5** | **8** |

### Epic 6: Session Agenda
| Historia | P50 | P90 |
|---|---|---|
| Como equipo Kisaco, creo y gestiono la agenda de sesiones desde el backoffice (título, speaker, horario, track, categoría) | 3 | 5 |
| Como attendee, navego la agenda del día filtrada por mi categoría de stakeholder | 3 | 5 |
| Como attendee, marco sesiones como favoritas para armar mi horario personal | 2 | 3 |
| **Subtotal** | **8** | **13** |

### Epic 7: Transactional Notifications
| Historia | P50 | P90 |
|---|---|---|
| Como attendee, recibo un email cuando un sponsor me envía una solicitud de reunión | 2 | 3 |
| Como sponsor, recibo un email cuando un attendee acepta o rechaza mi solicitud de reunión | 2 | 3 |
| **Subtotal** | **3** | **5** |

### Epic 8: Backoffice
| Historia | P50 | P90 |
|---|---|---|
| Como equipo Kisaco, incorporo attendees en bulk desde el sistema de registro | 3 | 5 |
| Como equipo Kisaco, configuro slots de reunión, salas y ventanas de disponibilidad para el evento | 3 | 5 |
| Como equipo Kisaco, reviso y overrideo sugerencias de match antes de que lleguen a los sponsors | 5 | 8 |
| Como equipo Kisaco, envío comunicaciones dirigidas a categorías específicas de stakeholders | 3 | 5 |
| Como equipo Kisaco, accedo a un dashboard en tiempo real con métricas del evento (matches, reuniones, show-up) | 5 | 8 |
| Como equipo Kisaco, exporto reportes de ROI por sponsor (matches, reuniones, asistencia, outcomes) | 3 | 5 |
| **Subtotal** | **21** | **29** |

---

### Resumen Stage 2A — Lean

| Epic | P50 | P90 ind. | Desvío² |
|---|---|---|---|
| Sponsor Matchmaking | 13 | 18 | 25 |
| Calendar Integration | 13 | 18 | 25 |
| Personalized Journeys | 21 | 29 | 64 |
| Show-up Tracking | 8 | 13 | 25 |
| Attendee Profile | 5 | 8 | 9 |
| Session Agenda | 8 | 13 | 25 |
| Transactional Notifications | 3 | 5 | 4 |
| Backoffice | 21 | 29 | 64 |
| **TOTAL** | **92** | — | **241** |

**P90 total (RSS) = 92 + √241 ≈ 92 + 15.5 = ~107 pts**

| Velocity | P50 sprints | P90 sprints | P50 meses | P90 meses |
|---|---|---|---|---|
| 20 pts/sprint | 4.6 | 5.4 | ~2.3 | ~2.7 |
| 15 pts/sprint | 6.1 | 7.1 | ~3.1 | ~3.6 |

**Timeline estimado: 3–4 meses**  
**Inversión: $76,500–$102,000** (a $25,500/mes de equipo)

---

## Stage 2B — Full (agrega sobre Lean)

### Epic 9: Full Stakeholder Coverage
| Historia | P50 | P90 |
|---|---|---|
| Como cualquiera de las 15 a 20 categorías de stakeholders, navego un journey construido para mi rol y objetivos específicos | 5 | 8 |
| Como equipo Kisaco, asigno y edito journeys por categoría desde una interfaz de admin | 5 | 8 |
| Como attendee, recibo recomendaciones de match enriquecidas con datos de fuentes externas | 3 | 5 |
| Como attendee, veo quién ha visto mi perfil o expresado interés en reunirse conmigo | 2 | 3 |
| **Subtotal** | **13** | **18** |

### Epic 10: Sponsor Self-Serve
| Historia | P50 | P90 |
|---|---|---|
| Como sponsor, ajusto mis criterios ICP y re-ejecuto el matching en tiempo real sin intervención del equipo Kisaco | 5 | 8 |
| Como equipo Kisaco, ejecuto matchmaking para 50+ sponsors simultáneamente desde un único dashboard | 5 | 8 |
| **Subtotal** | **8** | **13** |

### Epic 11: Post-Event Deal Intelligence
| Historia | P50 | P90 |
|---|---|---|
| Como sponsor, recibo actualizaciones post-evento cuando un contacto matcheado hace un movimiento de negocio relevante | 8 | 13 |
| Como account manager de Kisaco, comparto datos de relaciones y outcomes con sponsors después del evento | 5 | 8 |
| Como equipo Kisaco, uso datos de deal monitoring para demostrar ROI al sponsor y generar renovaciones | 5 | 8 |
| Como equipo Kisaco, configuro y activo el monitoreo post-evento por sponsor | 5 | 8 |
| **Subtotal** | **21** | **29** |

---

### Resumen Stage 2B — Full (delta sobre Lean)

| Epic | P50 | P90 ind. | Desvío² |
|---|---|---|---|
| Full Stakeholder Coverage | 13 | 18 | 25 |
| Sponsor Self-Serve | 8 | 13 | 25 |
| Post-Event Deal Intelligence | 21 | 29 | 64 |
| **Delta** | **42** | — | **114** |

**P90 delta (RSS) = 42 + √114 ≈ 42 + 10.7 = ~53 pts adicionales**

**Totales acumulados (Lean + Full):**
- P50 total = 92 + 42 = **134 pts**
- P90 total = 107 + 53 = **~160 pts** (conservador; en la práctica el RSS acumulado da ~155)

| Velocity | P50 sprints | P90 sprints | P50 meses | P90 meses |
|---|---|---|---|---|
| 20 pts/sprint | 6.7 | 8.0 | ~3.4 | ~4.0 |
| 15 pts/sprint | 8.9 | 10.7 | ~4.5 | ~5.4 |

**Timeline estimado: 4–6 meses** (sobre Lean; en modo secuencial)  
**Inversión acumulada: $102,000–$153,000**

---

## Resumen ejecutivo

| Versión | Pts P50 | Pts P90 | Timeline | Inversión |
|---|---|---|---|---|
| Stage 2A — Lean | 92 | 107 | 3–4 meses | $76,500–$102,000 |
| Stage 2B — Full (total) | 134 | ~160 | 4–6 meses | $102,000–$153,000 |

*Nota: Stage 1 (Discovery) se cotiza por separado: Option A $18,600 (5 semanas) / Option B $7,440 (2 semanas).*
