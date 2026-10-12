<!-- Seletor de Idioma / Language Selector -->
<p align="center">
  🌐 <b>Idiomas / Languages:</b> 
  <a href="#english">🇺🇸 English</a> | 
  <a href="#portugues">🇧🇷 Português</a>
</p>

---

<div id="english"></div>

# 🐧 Arus Linux

<p align="center">
  <b>A modern, stable, and elegant Linux distribution built on Debian Testing and KDE Plasma.</b>
</p>

<p align="center">
  <a href="#-about-the-project">About</a> •
  <a href="#-features">Features</a> •
  <a href="#-system-requirements">Requirements</a> •
  <a href="#-building-the-iso-chroot">Building</a> •
  <a href="#-license">License</a>
</p>

---

## 📌 About the Project

**Arus Linux** is a custom distribution designed to deliver a smooth, out-of-the-box experience optimized for both **Live USB sessions** and permanent hard drive installations. Built on top of robust **Debian Testing (Trixie)** packages and powered by **KDE Plasma**, it combines cutting-edge software with rock-solid stability and modern hardware integration.

---

## ✨ Features

* **Modern Base:** Debian Testing + customized KDE Plasma desktop.
* **No Snap Bloatware:** Strictly relies on native `APT` packages (with repository pinning) and `Flatpak` integration via KDE Discover.
* **Out-of-the-Box Virtualization:** Native **KVM / QEMU / Virt-Manager** setup with automatic user permission handling (`libvirt`, `kvm` groups applied natively via Calamares).
* **Enhanced Hardware Support:**
  * Integrated Intel Wi-Fi and common network firmware packages.
  * **Arus NVIDIA Installer:** A custom graphical utility (`kdialog`-based) to seamlessly detect, build, and configure NVIDIA proprietary/open drivers.
* **Custom Plymouth Experience:**
  * Custom animated boot theme (`arus`).
  * Dynamic shutdown/reboot message prompting users to remove the installation USB during Live sessions.

---

## 💻 System Requirements

| Component | Minimum | Recommended |
| :--- | :--- | :--- |
| **Processor** | 64-bit Dual Core | 64-bit Quad Core or better |
| **Memory (RAM)** | 2 GB | 4 GB or higher |
| **Storage** | 20 GB free space | 40 GB SSD |
| **Boot Media** | 4 GB+ USB Drive | 8 GB+ USB 3.0 Drive |

---

## 📥 Chroot Download (.tar.xz)

If you prefer to start with a pre-configured development environment rather than setting it up from scratch, you can download the base rootfs chroot archive:

* **[📥 Download Arus Linux RootFS (tar.xz)](https://drive.google.com/file/d/1JuRs5P_4m2hh2JY1Jw4dwqlAaCVPuzGq/view?usp=sharing)**

---

## 🛠️ Building the ISO (Chroot)

To configure or build Arus Linux locally inside a Debian environment:

### 1. Mount Virtual Directories
```bash
sudo mount --bind /dev /opt/debian-root/dev
sudo mount --bind /dev/pts /opt/debian-root/dev/pts
sudo mount --bind /proc /opt/debian-root/proc
sudo mount --bind /sys /opt/debian-root/sys
```

### 2. Enter Chroot Environment
```bash
sudo chroot /opt/debian-root
apt update && apt upgrade -y
```

---

## 📄 License

Distributed under the **GPL-3.0 License**. See [LICENSE](LICENSE) for more information.

---
---

<div id="portugues"></div>

# 🐧 Arus Linux

<p align="center">
  <b>Uma distribuição Linux moderna, elegante e estável baseada em Debian Testing e KDE Plasma.</b>
</p>

<p align="center">
  <a href="#-sobre-o-projeto">Sobre</a> •
  <a href="#-recursos-em-destaque">Recursos</a> •
  <a href="#-requisitos-do-sistema">Requisitos</a> •
  <a href="#-construcao-da-iso-chroot">Construção</a> •
  <a href="#-licenca">Licença</a>
</p>

---

## 📌 Sobre o Projeto

O **Arus Linux** é uma distribuição desenvolvida com o objetivo de entregar uma experiência *out-of-the-box* fluida e focada em facilidade de uso, tanto na sessão **Live USB** quanto após a instalação no disco rígido. 

Construído sobre a base sólida do **Debian Testing (Trixie)** e impulsionado pelo ambiente gráfico **KDE Plasma**, o sistema combina atualizações frequentes com estabilidade e integração nativa de hardware.

---

## ✨ Recursos em Destaque

* **Base Atualizada:** Debian Testing + KDE Plasma customizado.
* **Sem Snap por Defeito:** Foco em pacotes nativos `APT` (com bloqueio via *pinning*) e ecossistema `Flatpak` integrado através do KDE Discover.
* **Virtualização de Alta Performance:** Integração nativa de **KVM / QEMU / Virt-Manager** com permissões automáticas geridas pelo instalador Calamares (`libvirt` e `kvm`).
* **Suporte Simplificado a Hardware:**
  * Firmwares e drivers Wi-Fi Intel integrados de fábrica.
  * **Arus NVIDIA Installer:** Utilitário gráfico nativo (via `kdialog`) para detetar, compilar e instalar drivers NVIDIA com apenas um clique.
* **Experiência Visual Customizada:**
  * Tema de boot/shutdown personalizado com **Plymouth**.
  * Mensagem dinâmica no encerramento da sessão Live orientando a remoção do pendrive.

---

## 💻 Requisitos do Sistema

| Componente | Mínimo | Recomendado |
| :--- | :--- | :--- |
| **Processador** | 64-bit Dual Core | 64-bit Quad Core ou superior |
| **Memória RAM** | 2 GB | 4 GB ou mais |
| **Armazenamento** | 20 GB de espaço livre | 40 GB SSD |
| **Mídia de Boot** | Pendrive USB de 4 GB+ | Pendrive USB de 8 GB+ (USB 3.0) |

---


## 📥 Download do Chroot (.tar.xz)

Se preferir utilizar um ambiente base já pré-configurado em vez de o criar do zero, pode descarregar o pacote rootfs compactado:

* **[📥 Baixar Arus Linux RootFS (tar.xz)](https://drive.google.com/file/d/1JuRs5P_4m2hh2JY1Jw4dwqlAaCVPuzGq/view?usp=sharing)**

---

## 🛠️ Construção da ISO (Chroot)

Para preparar ou compilar o ambiente do Arus Linux localmente:

### 1. Montar Diretórios Virtuais
```bash
sudo mount --bind /dev /opt/debian-root/dev
sudo mount --bind /dev/pts /opt/debian-root/dev/pts
sudo mount --bind /proc /opt/debian-root/proc
sudo mount --bind /sys /opt/debian-root/sys
```

### 2. Entrar no Ambiente Chroot
```bash
sudo chroot /opt/debian-root
apt update && apt upgrade -y
```

---

## 📄 Licença

Este projeto é distribuído sob a licença **GPL-3.0**. Consulte o ficheiro [LICENSE](LICENSE) para mais detalhes.

---
<p align="center">
  Desenvolvido com ❤️ pela comunidade <b>Arus Linux</b>.
</p>
