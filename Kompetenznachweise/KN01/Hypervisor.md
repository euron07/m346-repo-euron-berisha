# Hypervisor (Typ 1 vs. Typ 2)

## Was ist ein Hypervisor?
Ein Hypervisor ist ein Programm, das dafür sorgt, dass man auf einem einzigen Computer mehrere **virtuelle Computer (VMs)** gleichzeitig laufen lassen kann und der Hypervisor verwaltet die Ressourcenverteilung für die VMs.  

<img width="654" height="379" alt="image" src="https://github.com/user-attachments/assets/e6770631-5e49-4068-8981-48cf1d586515" />

---

## Typ 1 Hypervisor (Bare-Metal)
- Läuft direkt auf der Hardware (also ohne ein extra Betriebssystem dazwischen).  
- **Vorteile:** Sehr schnell, sicher und stabil und wird in Rechenzentren oder bei Cloud-Anbietern genutzt.  
- **Nachteil:** Etwas komplizierter einzurichten und zu verwalten.  

**Beispiele:** VMware ESXi, Microsoft Hyper-V, KVM

---

## Typ 2 Hypervisor (Hosted)
- Läuft als ganz normales Programm auf einem vorhandenen Betriebssystem (z.b Windows).  
- **Vorteile:** Einfach zu installieren und zu bedienen, ideal zum Lernen und testen oder für Entwickler.  
- **Nachteile:** Weniger Leistung und etwas unsicherer, weil alles über das Host-Betriebssystem läuft.  

 **Beispiele:** VirtualBox, VMware Workstation 

---

## Vergleich in Kurzform (Bild von der Quelle)

<img width="1022" height="624" alt="image" src="https://github.com/user-attachments/assets/a197218e-e195-4115-be32-c42624eb91a5" />



**Quelle:**  
[AWS – Unterschied zwischen Typ 1 und Typ 2 Hypervisoren](https://aws.amazon.com/de/compare/the-difference-between-type-1-and-type-2-hypervisors/)



