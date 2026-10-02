
# **AI-prompt & svar**

## Varje prompt kommer att få en egen undertitel

<!-- Jag tappade tyvärr bort någon prompt då jag gjorde allt så snabbt, jag har gjort om allt flera gånger. Jag tror det enda jag promptade var då jag skapade .md filerna. För att se process med alla filer så se **skärmbilder** -->

Första prompt:
Jag har skapat mitt git repo. Detta är vad som finns inuti repo. PS C:\Users\curze\Desktop\Git\Skola\GitFörstaLabb> dir



    Directory: C:\Users\curze\Desktop\Git\Skola\GitFörstaLabb



Mode                 LastWriteTime         Length Name

----                 -------------         ------ ----

d----          2026-10-02    21:01                Ai-Logg

d----          2026-10-02    20:51                Misstag

d----          2026-10-02    20:50                Skärmdumpar

-a---          2026-10-02    21:24             61 .gitignore

-a---          2026-10-02    20:53              0 Labbrapport.md

-a---          2026-10-02    20:52              0 READme.md

.



Jag vill nu att du ger mig en färdig mall. Detta ska jag skriva i min labbrapport.md och ska skrivas i md format. Skapa hela mallen åt mig. Börja med titel & introduktion sedan namn, datum, kurs och kort beskrivning av labbmiljön. med alla tillhörande titlar, subtitlar, filer. med 

## Ai gav detta svar:
# Labbrapport: Virtuell Labbmiljö, Git, CLI och AI

* **Namn:** [Ditt Namn]
* **Datum:** 2026-10-02
* **Kurs:** Introduktion till yrkesrollen och grunderna i IT-infrastruktur (MYH 2025/4008)
* **Repository:** `GitFörstaLabb`

---

## 1. Introduktion & Beskrivning av Labbmiljön

Denna labbrapport dokumenterar uppsättningen och konfigurationen av en virtuell labbmiljö bestående av två virtuella maskiner: en Linux-server och en Windows-klient/server. Syftet med labben är att demonstrera praktiska färdigheter inom nätverskonfiguration, grundläggande kommandoradsarbete (CLI), behörighetshantering i både Linux och Windows, versionshantering med Git samt en kritisk utvärdering av AI som arbetsverktyg.

---

## 2. Labbmiljö & Nätverk (Kursmål 8)

Båda de virtuella maskinerna är placerade på ett gemensamt internt nätverk för att möjliggöra isolerad kommunikation och felsökning.

### Nätverkstabell

| Hostname | Operativsystem | IP-adress | Subnätmask | Standard Gateway |
| :--- | :--- | :--- | :--- | :--- |
| `Linux-Server` | Ubuntu Server / Debian | `192.168.1.50` | `255.255.255.0` (`/24`) | `192.168.1.1` |
| `Win-Klient` | Windows 10/11 / Win Server | `192.168.1.51` | `255.255.255.0` (`/24`) | `192.168.1.1` |

---

## 3. Kommandoradsarbete & Felsökning (Kursmål 9)

### 3.1 Linux (Bash)

1. **Skapa mapp och fil via CLI:**
   ```bash
   sudo mkdir -p /var/systementor/konsultdata
   sudo touch /var/systementor/konsultdata/anteckningar.txt

 <!-- Detta gillade jag inte. Lägger själv till moment vid git repo - se färdig labbrapport för resultat -->