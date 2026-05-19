# ☁️ Servidor al Núvol amb GitHub Codespaces (Alumne 04)

## 🎯 Descripció del Projecte
Aquest projecte consisteix en la creació, configuració i desplegament d'un servidor Linux (Ubuntu) allotjat al núvol utilitzant la infraestructura integrada de **GitHub Codespaces**. El servidor ofereix serveis d'administració remota i un servidor web Apache amb dues seccions completament diferenciades: una zona pública d'accés lliure i una zona privada restringida mitjançant autenticació bàsica HTTP.

## 💻 La Màquina Virtual Integrada
L'entorn de treball s'executa sobre un **Codespace**, que és un contenidor virtualitzat basat en Linux (Ubuntu) allotjat als servidors cloud de GitHub. Aquesta tecnologia permet disposar d'un sistema operatiu complet amb la seva pròpia consola, gestió d'usuaris i capacitat de xarxa sense consumir recursos de la màquina local de l'alumne.

## 🚀 Passos bàsics per posar en marxa el servidor

Si es vol replicar o reiniciar aquest servidor des de zero dins del Codespace, s'han d'executar les següents ordres a la terminal:

### 1. Actualització del sistema i instal·lació d'Apache
```bash
sudo apt update
sudo apt install apache2 -y
