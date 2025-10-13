# Proposta de domini i hosting per al client Diari del Barri

## 1. Presentació del client
- **Breu descripció del negoci:**  
  Diari del Barri és un mitjà digital local que publica notícies diàries sobre actualitat i esdeveniments de la comunitat.

- **Objectius principals de la web:**  
  Garantir rapidesa en la càrrega, seguretat contra atacs (WAF) i còpies de seguretat freqüents. La web es mantindrà amb actualitzacions constants i trànsit alt.

- **Requeriments tècnics identificats:**  
  CMS optimitzat (WordPress), WAF, còpies automàtiques, ample de banda alt, hosting escalable, suport en català i SEO local.

---

## 2. Anàlisi de dominis
- **Criteris per al naming (identitat, SEO, extensió preferida):**  
  Nom periodístic i local per reforçar la identitat territorial. Extensió recomanada `.cat` per a mitjans catalans o `.news` com a alternativa global.

- **Alternatives de dominis disponibles (octubre 2025):**  
  - `diaridelbarri.cat` – disponible (~14 €/any)  
  - `diaridelbarri.news` – disponible (~18 €/any)  
  - `eldiariodelbarri.cat` – disponible (~15 €/any)

- **Recomanació final de domini:**  
  **diaridelbarri.cat** — reforça la identitat local i millora el posicionament entre el públic català.

---

## 3. Comparativa de hostings (octubre 2025)
| Proveïdor | Espai disc | Transferència | Preu mensual* | Pros | Contres |
|------------|------------|----------------|----------------|-------|----------|
| **Webempresa Standard** | 11 GB SSD NVMe | Il·limitada | **7,95 €** | WAF, còpies cada 4 h, suport WordPress, en català | Espai limitat |
| **SiteGround GrowBig** | 20 GB SSD | Il·limitada | **9,99 €** | WAF integrat, entorn staging, còpies diàries | Preu més alt |
| **OVH Pro** | 500 GB SSD | Il·limitada | **5,99 €** | Gran capacitat, bon preu | Sense WAF avançat |
| **Raiola Networks WordPress Pro** | 15 GB SSD | Il·limitada | **8,95 €** | Suport especialitzat, còpies diàries | Espai menor |

\*Preus reals (octubre 2025) segons les webs oficials dels proveïdors.

---

## 4. Checklist de requeriments complerts
- [x] **SSL inclòs** – SiteGround/Webempresa amb Let's Encrypt  
- [x] **Backups automàtics freqüents** – Cada 4 h (Webempresa)  
- [x] **WAF** – Integrat als plans de seguretat  
- [x] **CMS WordPress** – Suport total i optimització  
- [ ] **CDN integrat** – Activar Cloudflare (pla gratuït)  
- [ ] **Correu corporatiu** – Opcional via Zoho Mail / Google Workspace  
- [x] **RGPD i cookies** – Política de privacitat i avís legal  
- [ ] **Entorn de staging** – Disponible a SiteGround GrowBig / crear subdomini “staging”  
- [x] **Monitoratge i alertes** – Configurar UptimeRobot  
- [ ] **SLA i escalabilitat (pla B)** – Documentar 99,9 % uptime i migració VPS (OVH/AWS)  

---

## 5. Recomanació final
- **Hosting escollit:** Webempresa Standard  
- **Domini recomanat:** `diaridelbarri.cat`  
- **Justificació:**  
  Webempresa ofereix un equilibri excel·lent entre seguretat, rendiment i servei en català, amb còpies freqüents i WAF. Ideal per a mitjans locals amb trànsit alt i contingut diari.

---

## 6. Conclusions
- **Criteris decisius:** Seguretat, freqüència de còpies, rendiment i suport local.  
- **Per què és la millor opció:**  
  Webempresa garanteix estabilitat, protecció i suport tècnic en català, assegurant un servei fiable i ràpid.

---

## 7. Costos anuals estimats
| Concepte | Cost mensual | Cost anual aproximat |
|-----------|---------------|----------------------|
| Hosting (Webempresa Standard) | 7,95 € | 95,40 € |
| Domini `.cat` | — | 14 € |
| **Total anual estimat** | — | **≈ 109 €** |
