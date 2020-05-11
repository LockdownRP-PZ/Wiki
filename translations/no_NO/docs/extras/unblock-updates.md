# Unblocking Updates
---
This is needed if you ever need to perform a System Update.

### Instruksjoner

<!-- tabs:start -->

#### **Recreating The Update Folder**

?> For å gjøre dette, må Wii U konsollen være på samme nettverk som PC'en din.
1. Sett SD-kortet inn i PC'en din.
1. Last ned og pakk ut [ftpiiu_everywhere](http://wiiubru.com/appstore/zips/fpiiu-cbhc.zip) til roten av SD-kortet ditt.
1. Last ned en FTP-klient, som for eksempel [FileZilla](https://filezilla-project.org/download.php?show_all=1).
1. Sett SD-kortet inn i Wii U konsollen og skru den på.
1. Start CFW (Mocha, Haxchi/CBHC) og start opp Homebrew Launcher.
1. I Homebrew Launcher, kjør ftpiiu_everywhere appen.
1. Noter IP-adressen på Wii U-skjermen.
1. På PC'en din starter du FTP-klienten din, og start en FTP-tilkobling til Wii U konsollen. I FileZilla skriver du bare IP-adressen fra Wii U'en inn i "Host" vindu under verktøylinja og trykker "Quickconnect": <br><img src="docs/assets/img/FTP.png" alt="FileZilla" />
1. Naviger til `/storage_mlc/sys`.
1. Create a folder named `update`.
1. You are now no longer blocking system updates.

### **Removing The DNS Blocks**

1. Enter the Wii U's system settings and navigate to `Internet > Connect to the Internet > Connection List >` `Your WiFi connection > Change Settings > DNS` and set the option to `Auto-obtain`.
1. You are now no longer blocking system updates.

<!-- tabs:end -->