# Mi Homelab

Documentación viva de la infraestructura de mi homelab: hardware, virtualización, almacenamiento, backups y monitoreo.

## 🖥️ Hardware
| Componente | Especificación |
|------------|-----------------|
| Servidor   | ...             |
| RAM        | ...             |
| Storage    | ...             |
| Red        | ...             |

## 🗂️ Virtualización
- Hipervisor: Proxmox / ESXi
- VMs/LXC desplegados: [lista con propósito de cada uno]

## 💾 Storage
- [NFS / iSCSI — configuración, pools, redundancia]

## 🔄 Backups
- Herramienta: [Proxmox Backup Server, restic, etc.]
- Frecuencia y retención: [...]
- **Prueba de restauración realizada:** [fecha y resultado — esto es clave, no solo digas que hay backups]

## 📊 Monitoreo
- Prometheus + Grafana
- [Qué métricas monitoreas: CPU, RAM, temperatura, uptime de servicios]

![Dashboard](diagrams/grafana-dashboard.png)

## 🗺️ Diagrama de red del homelab
![Topología](diagrams/homelab-topology.png)

## 📚 Evolución
[Bitácora de cambios importantes: "agregué monitoreo en [fecha]", "migré storage a ZFS en [fecha]"]
