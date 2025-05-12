# DocEvo

# Azure ARM Templates Export & Flattening Tools

Este repositorio contiene scripts en PowerShell para automatizar la exportación de plantillas ARM desde grupos de recursos en Azure y para aplanar objetos complejos en estructuras clave-valor simples.

---

## 📁 Contenido

- `scripts/doc_v1.ps1`: Exporta plantillas ARM de todos los grupos de recursos en una suscripción de Azure.
- `scripts/doc.2.1.4_OK_System.Management.Automation.OrderedHashtable.ps1`: Aplana objetos complejos como `hashtable` o `OrderedHashtable`.

---

## 🚀 Uso

### 1. Exportar Plantillas ARM

```powershell
cd scripts
.\doc_v1.ps1
