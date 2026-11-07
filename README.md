# 🔸 MoG AUTOMATION (`mogautomation-arch`) · Ingeniería, Automatización y MESA · MoG CORPORATION

**Identidad de Cuenta GitHub:** `mogautomation-arch` (`credential_group: mog-automation`)  
**Organización Rectora:** `mog-corporation` (**MoG CORPORATION** · **Eco-Logics Control Clima S.L.** · **Ingeteyco S.L.** · **Inversiones MoG S.L.**)  
**Autoridad Soberana:** D. Miguel Ortega (`🔶 MoG CEo & ARQ`)  

---

## 1. Rol Contractual y Segregación `writer != verifier`
- **`mogautomation-arch`** actúa como cuenta de **escritura, empuje de ramas (`pusher`) y automatización técnica** dentro del `credential_group: mog-automation`.
- **Segregación Inmutable:** Conforme a la Regla de Organización («Verificador independiente del stack», `05/11/2026`), `mogautomation-arch` **nunca da su propio conforme sobre código escrito por su propio grupo**. La verificación independiente corresponde a **`mog-verificador`** (`credential_group: mog-verificador`, equipo `Verificadores`) y a los runners verificadores independientes (`ANTI_RUNNER_0001`).
- **Fusión Centralizada en MESA:** Toda fusión (`--squash --match-head-commit <HEAD>`) requiere `mide_resenas.py = LISTO` (`exit 0`), sin etiqueta `HOLD`, sin hilos abiertos, sin hallazgos de seguridad pendientes y con readback `merged=true`.

## 2. Repositorios Gobernados Aterrizados (`9/9`)
| Repositorio | Ruta Local Gobernada (`ECOLOGICS02` / `M1`) | Función en el Stack |
|---|---|---|
| `mog-corporation/mog-universe` | `C:\mog-universe` y `C:\ProgramData\MoG\Automation\git\mog-universe` | Fuente canónica de reglas, `CODIGO_CANON`, 83 skills MoG y 10 perfiles |
| `mog-corporation/mog-suite` | `C:\mog-suite` y `C:\ProgramData\MoG\Automation\git\mog-suite` | Frente de 11 APPS y 5 Sedes de Superadmin |
| `mog-corporation/mog-containers-m1` | `C:\mog-containers-m1` y `C:\ProgramData\MoG\Automation\git\mog-containers-m1` | Contenedores aislados de agentes M1 (`WIP=1`, cero secretos) |
| `mog-corporation/mog-federation` | `C:\ProgramData\MoG\Automation\git\mog-federation` | Capa federativa por empresa, departamento y cargo |
| `mog-corporation/mog-control-plane` | `C:\ProgramData\MoG\Automation\git\mog-control-plane` | Servicio Cloud Run `mog-control-plane` |
| `mog-corporation/mogbot-personal-skills` | `C:\ProgramData\MoG\Automation\git\mogbot-personal-skills` | Skills privadas de dirección y patrimonio |
| `mog-corporation/mogautomation-arch` | `C:\ProgramData\MoG\Automation\git\mogautomation-arch` | Motores de mantenimiento multi-repo y auto-merge gobernado |
| `mog-corporation/mog-data-engine` | `C:\ProgramData\MoG\Automation\git\mog-data-engine` | Motor de datos gobernado de MoG Corporation |
| `mogautomation-arch/mog-comms-gateway` | `C:\ProgramData\MoG\Automation\git\mog-comms-gateway` | Control plane de eventos, relays durables y leases |

## 3. Contenedores Operativos (`9/9`) y Brain Compartido (`C:\BRAIN_MOG`)
- **Contenedores Activos:** `C:\MOG_MESA`, `C:\ANTIGRAVITY_HUB_C`, `C:\CLAUDE_HUB_C`, `C:\CODEX_HUB_C`, `C:\COPILOT_HUB_C`, `C:\ECO_HUB_C`, `C:\GEMINI_HUB_C`, `C:\QODER_HUB_C`, `C:\MOG_NODO_ERP_OFICINA`.
- **Puente Local Loopback:** `http://127.0.0.1:8787` (`/health`, `/sesiones-enlaces`, `/comms-local`, `/vigia-uso-gasto`).
- **Skills Aterrizadas:** **149 skills únicas** (`83` MoG + `9` Builtin + `22` Plugins + `6` Codex + `29` Claude Marketplace) y **10 perfiles MoG**.

---
*Firma Canónica:*  
**`🔸 MoGbot MESA Antigravity · Orquestador de Verificación y Fusión Centralizada · MoG CORPORATION`**
