# Virtualisierungssoftware
---
**PC-specs:**
- 16 GB Ram
- 16 CPU
---

Ich habe mit **Oracle VirtualBox** gearbeitet.  
**erste Vermutung:** VirtualBox ist ein **Hypervisor Typ 2**, weil es auf dem Host-Betriebssystem läuft und auf dem Betriebssystem heruntergeladen wurde.  

Beim Test konnte ich nicht mehr CPUs oder RAM zuweisen, als mein PC tatsächlich hat.  

**Erklärung:** VirtualBox blockiert eine höhere Zuweisung, damit der Host stabil bleibt.  
Meine Vermutung (Typ 2) hat sich bestätigt.

## Screenshots

**1. Ausgabe in der VM (`lscpu` und `free -h`):**  
Die eingestellten Werte werden angezeigt.
![b69d0743-9fa5-4a50-bb13-8f93a2f1f827](https://github.com/user-attachments/assets/a26b0235-1998-412b-a62f-af7763898e2f)


**2. CPU-Einstellungen in VirtualBox:**  
![2887c223-c53e-4a80-a810-2f87b6a47641](https://github.com/user-attachments/assets/5be08337-7e2a-47a2-92ec-c79511567907)


**3. RAM-Einstellungen in VirtualBox:**  
![114b19a1-a72b-43a6-8895-5bc980341b55](https://github.com/user-attachments/assets/2e34bc0d-7d6a-4710-8e87-a79cb859276b)


