<!-- Seletor de Idioma no Topo -->
<p align="center">
  <a href="#english">🇺🇸 English</a> | <a href="#portugues">🇧🇷 Português</a>
</p>

---

<!-- ==================== VERSÃO EM INGLÊS ==================== -->
<div id="english"></div>

# 🐧 Arus Linux

<p align="center">
<img src="https://raw.githubusercontent.com/seu-usuario/arus-linux/main/assets/logo.png" alt="Arus Linux Logo" width="180"/>
</p>

<p align="center">
<b>A modern, elegant, and stable Linux distribution based on Debian Testing and KDE Plasma.</b>
</p>

<p align="center">
<a href="#-about-the-project">About</a> •
<a href="#-key-features">Features</a> •
<a href="#-downloads">Downloads</a> •
<a href="#%EF%B8%8F-iso-build-chroot">ISO Build</a> •
<a href="#-contribution">Contribution</a> •
<a href="#-license">License</a>
</p>

---

## 📌 About the Project

**Arus Linux** is a distribution developed with the goal of delivering a smooth, user-friendly, *out-of-the-box* experience—both in the **Live USB** environment and after installation on the hard drive.

Built upon the solid foundation of **Debian Testing (Trixie)** and powered by the **KDE Plasma** desktop environment, the system combines frequent package updates with stability, native hardware integration, and productivity tools.

---

## ✨ Key Features

* **Up-to-date Base:** Debian Testing + customized KDE Plasma.
* **No Snapd by Default:** Focus on native `APT` packages (with blocking via *pinning*) and a `Flatpak` ecosystem integrated via KDE Discover.
* **High-Performance Virtualization:** Native integration of **KVM / QEMU / Virt-Manager** with pre-configured user permissions. * **Streamlined Hardware Support:**
* Integrated Intel Wi-Fi firmware and drivers. 
* Native graphical utility (**Arus NVIDIA Installer**) for proprietary driver detection and compilation.
* **Customized Visual Experience:**
* Custom boot/shutdown theme using **Plymouth**. 
* Dynamic prompt to remove installation media during the Live session.
* **Hassle-free Installation:** Calamares configured to preserve system groups (`libvirt`, `kvm`, `sudo`).

---

## 💻 System Requirements

| Component | Minimum | Recommended |
| :--- | :--- | :--- |
| **Processor** | 64-bit Dual Core | 64-bit Quad Core or higher |
| **RAM** | 2 GB | 4 GB or more |
| **Storage** | 20 GB free space | 40 GB SSD |
| **Boot Media** | 4 GB+ USB drive | 8 GB+ USB drive (USB 3.0) |

---

## 🛠️ ISO Build (Chroot)

If you wish to build the Arus Linux ISO locally on your Debian/Ubuntu system:

### 1. Clone the Repository
```bash
git clone https://github.com/gabrielplays0404/arus-linux.git
cd arus-linux

---

<!-- ==================== VERSÃO EM PORTUGUÊS ==================== -->
<div id="portugues"></div>

# 🐧 Arus Linux

<p align="center">
  <img src="https://raw.githubusercontent.com/seu-usuario/arus-linux/main/assets/logo.png" alt="Arus Linux Logo" width="180"/>
</p>

<p align="center">
  <b>Uma distribuição Linux moderna, elegante e estável baseada em Debian Testing e KDE Plasma.</b>
</p>

<p align="center">
  <a href="#-sobre-o-projeto">Sobre</a> •
  <a href="#-recursos-em-destaque">Recursos</a> •
  <a href="#-downloads">Downloads</a> •
  <a href="#%EF%B8%8F-construcao-da-iso-chroot">Construção da ISO</a> •
  <a href="#-contribuicao">Contribuição</a> •
  <a href="#-licenca">Licença</a>
</p>

---

## 📌 Sobre o Projeto

O **Arus Linux** é uma distribuição desenvolvida com o objetivo de entregar uma experiência *out-of-the-box* fluida e focada em facilidade de uso, tanto no ambiente **Live USB** quanto após a instalação no disco rígido. 

Construído sobre a base sólida do **Debian Testing (Trixie)** e impulsionado pelo ambiente gráfico **KDE Plasma**, o sistema combina atualizações frequentes de pacotes com estabilidade, integração nativa de hardware e ferramentas de produtividade.

---

## ✨ Recursos em Destaque

* **Base Atualizada:** Debian Testing + KDE Plasma customizado.
* **Sem Snapd por Defeito:** Foco em pacotes nativos `APT` (com bloqueio via *pinning*) e ecossistema `Flatpak` integrado via KDE Discover.
* **Virtualização de Alta Performance:** Integração nativa de **KVM / QEMU / Virt-Manager** com permissões de utilizador pré-configuradas.
* **Suporte Simplificado a Hardware:**
  * Firmwares e drivers Wi-Fi Intel integrados.
  * Utilitário gráfico nativo (**Arus NVIDIA Installer**) para deteção e compilação de drivers proprietários.
* **Experiência Visual Personalizada:**
  * Tema de boot/shutdown personalizado com **Plymouth**.
  * Mensagem dinâmica de orientação para remoção da mídia de instalação durante a sessão Live.
* **Instalação Descomplicada:** Calamares configurado para manter integrados os grupos do sistema (`libvirt`, `kvm`, `sudo`).

---

## 💻 Requisitos do Sistema

| Componente | Mínimo | Recomendado |
| :--- | :--- | :--- |
| **Processador** | 64-bit Dual Core | 64-bit Quad Core ou superior |
| **Memória RAM** | 2 GB | 4 GB ou mais |
| **Armazenamento** | 20 GB de espaço livre | 40 GB SSD |
| **Mídia de Boot** | Pendrive USB de 4 GB+ | Pendrive USB de 8 GB+ (USB 3.0) |

---

## 🛠️ Construção da ISO (Chroot)

Se deseja compilar a ISO do Arus Linux localmente no seu sistema Debian/Ubuntu:

### 1. Clonar o Repositório
```bash
git clone https://github.com/gabrielplays0404/arus-linux.git
cd arus-linux
