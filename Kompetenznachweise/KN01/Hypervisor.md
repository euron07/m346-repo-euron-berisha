# Hypervisor (Typ 1 vs. Typ 2)

## Was ist ein Hypervisor?
Ein **Hypervisor** ist ein Programm, das dafür sorgt, dass man auf einem einzigen Computer mehrere **virtuelle Computer (VMs)** gleichzeitig laufen lassen kann.  
Jede virtuelle Maschine bekommt dabei ihre eigenen "künstlichen" Teile wie Prozessor, Arbeitsspeicher und Festplatte. So kann man z. B. Windows und Linux gleichzeitig auf demselben Rechner nutzen.

---

## Typ 1 Hypervisor (Bare-Metal)
- Läuft **direkt auf der Hardware** (also ohne ein extra Betriebssystem dazwischen).  
- **Vorteile:** Sehr schnell, sicher und stabil – wird in Rechenzentren oder bei Cloud-Anbietern genutzt.  
- **Nachteil:** Etwas komplizierter einzurichten und zu verwalten.  

**Beispiele:** VMware ESXi, Microsoft Hyper-V, KVM, Xen  

---

## Typ 2 Hypervisor (Hosted)
- Läuft **als ganz normales Programm auf einem vorhandenen Betriebssystem** (z. B. Windows oder macOS).  
- **Vorteile:** Einfach zu installieren und zu bedienen, ideal zum Lernen, Testen oder für Entwickler.  
- **Nachteile:** Weniger Leistung und etwas unsicherer, weil alles über das Host-Betriebssystem läuft.  

 **Beispiele:** VirtualBox, VMware Workstation, Parallels  

---

## Vergleich in Kurzform

| Merkmal       | Typ 1 (Bare-Metal)          | Typ 2 (Hosted)               |
|---------------|-----------------------------|------------------------------|
| Start         | Direkt auf Hardware         | Läuft in einem Betriebssystem |
| Leistung      | Sehr hoch                   | Weniger, da OS dazwischen    |
| Sicherheit    | Hoch                        | Weniger, hängt vom Host ab   |
| Bedienung     | Komplexer                   | Einfacher                    |
| Einsatz       | Server, Cloud, Rechenzentren| Zuhause, Schule, Testsysteme |


**Quelle:**  
[AWS – Unterschied zwischen Typ 1 und Typ 2 Hypervisoren](https://aws.amazon.com/de/compare/the-difference-between-type-1-and-type-2-hypervisors/)


<img width="654" height="379" alt="image" src="https://github.com/user-attachments/assets/e6770631-5e49-4068-8981-48cf1d586515" />

