---
title: Operating Systems
description: Privacy-hardened operating systems and firmware for phones, desktops, and routers.
weight: 50
---

## Custom Android Distributions

<div class="pg-card-logos">
{{< cards >}}
  {{< card link="android/distributions/index.md#grapheneos" title="GrapheneOS" image="android/distributions/grapheneos.svg" subtitle="GrapheneOS hardens the Android stack on supported Pixels with verified boot, firmware updates, and sandboxed Play." >}}
{{< /cards >}}
</div>

## Android General Apps

<div class="pg-card-logos">
{{< cards >}}
  {{< card link="android/general-apps/index.md#shelter" title="Shelter" image="android/general-apps/shelter.svg" subtitle="Shelter uses a managed work profile to isolate or duplicate apps with optional cross-profile controls." >}}
  {{< card link="android/general-apps/index.md#secure-camera" title="Secure Camera" image="android/general-apps/secure_camera.svg" subtitle="Secure Camera captures media with minimal metadata and modern Android storage APIs." >}}
  {{< card link="android/general-apps/index.md#secure-pdf-viewer" title="Secure PDF Viewer" image="android/general-apps/secure_pdf_viewer.svg" subtitle="Secure PDF Viewer renders PDFs in a sandboxed WebView without broad file permissions." >}}
{{< /cards >}}
</div>

## Obtaining Android Apps

<div class="pg-card-logos">
{{< cards >}}
  {{< card link="android/obtaining-apps/index.md#obtainium" title="Obtainium" image="android/obtaining-apps/obtainium.svg" subtitle="Obtainium is an app manager which allows you to install and update apps directly from the developer’s own releases page (i.e. GitHub, GitLab, the developer’s website, etc.), rather than a centralized app store/repository." >}}
  {{< card link="android/obtaining-apps/index.md#grapheneos-app-store" title="GrapheneOS App Store" subtitle="GrapheneOS’s app store is available on GitHub. It supports Android 12 and above and is capable of updating itself. The app store has standalone applications built by the GrapheneOS project such as the Auditor, Camera, and PDF Viewer." >}}
  {{< card link="android/obtaining-apps/index.md#aurora-store" title="Aurora Store" image="android/obtaining-apps/aurora-store.webp" subtitle="Aurora Store is a Google Play Store client which does not require a Google account, Google Play Services, or microG to download apps." >}}
  {{< card link="android/obtaining-apps/index.md#f-droid" title="F-Droid" image="android/obtaining-apps/f-droid.svg" subtitle="We only recommend F-Droid as a way to obtain apps which cannot be obtained via the means above. F-Droid is often recommended as an alternative to Google Play, particularly within the privacy community. The option to add third-party repositories and not be confined to Google’s walled garden has led to its popularity." >}}
{{< /cards >}}
</div>

## Desktop/PC

<div class="pg-card-logos">
{{< cards >}}
  {{< card link="desktop/index.md#fedora-linux" title="Fedora Linux" image="desktop/fedora.svg" subtitle="Fedora Linux is our recommended desktop distribution for people new to Linux. Fedora generally adopts newer technologies (e.g., Wayland and PipeWire) before other distributions. These new technologies often come with improvements in security, privacy, and usability in general." >}}
  {{< card link="desktop/index.md#opensuse-tumbleweed" title="openSUSE Tumbleweed" image="desktop/opensuse-tumbleweed.svg" subtitle="openSUSE Tumbleweed is a stable rolling release distribution. openSUSE Tumbleweed uses Btrfs and Snapper to ensure that snapshots can be rolled back should there be a problem." >}}
  {{< card link="desktop/index.md#arch-linux" title="Arch Linux" image="desktop/archlinux.svg" subtitle="Arch Linux is a lightweight, do-it-yourself (DIY) distribution, meaning that you only get what you install. For more information see their FAQ." >}}
  {{< card link="desktop/index.md#fedora-atomic-desktops" title="Fedora Atomic Desktops" image="desktop/fedora.svg" subtitle="Fedora Atomic Desktops are variants of Fedora which use the rpm-ostree package manager and have a strong focus on containerized workflows and Flatpak for desktop applications. All of these variants follow the same release schedule as Fedora Workstation, benefiting from the same fast updates and staying very close to upstream." >}}
  {{< card link="desktop/index.md#nixos" title="NixOS" image="desktop/nixos.svg" subtitle="NixOS is an independent distribution based on the Nix package manager with a focus on reproducibility and reliability." >}}
  {{< card link="desktop/index.md#whonix" title="Whonix" image="desktop/whonix.svg" subtitle="Whonix is based on Kicksecure, a security-focused fork of Debian. It aims to provide privacy, security, and anonymity on the internet. Whonix is best used in conjunction with Qubes OS." >}}
  {{< card link="desktop/index.md#tails" title="Tails" image="desktop/tails.svg" subtitle="Tails is a live operating system based on Debian that routes all communications through Tor, which can boot on on almost any computer from a DVD, USB stick, or SD card installation. It uses Tor to preserve privacy and anonymity while circumventing censorship, and it leaves no trace of itself on the computer it is used on after it is powered off." >}}
  {{< card link="desktop/index.md#qubes-os" title="Qubes OS" image="desktop/qubes_os.svg" subtitle="Qubes OS is an open-source operating system designed to provide strong security for desktop computing through secure virtual machines (or “qubes”). Qubes is based on Xen, the X Window System, and Linux. It can run most Linux applications and use most of the Linux drivers." >}}
  {{< card link="desktop/index.md#secureblue" title="Secureblue" image="desktop/secureblue.svg" subtitle="Secureblue is a security-focused operating system based on Fedora Atomic Desktops. It includes a number of security features intended to proactively defend against the exploitation of both known and unknown vulnerabilities, and ships with Trivalent, their hardened, Chromium-based web browser." >}}
  {{< card link="desktop/index.md#kicksecure" title="Kicksecure" image="desktop/kicksecure.svg" subtitle="Kicksecure—in oversimplified terms—is a set of scripts, configurations, and packages that substantially reduce the attack surface of Debian. It covers a lot of privacy and hardening recommendations by default. It also serves as the base OS for Whonix." >}}
{{< /cards >}}
</div>

## Router Firmware

<div class="pg-card-logos">
{{< cards >}}
  {{< card link="router-firmware/index.md#openwrt" title="OpenWrt" image="router-firmware/openwrt.svg" subtitle="OpenWrt is a Linux-based operating system; it’s primarily used on embedded devices to route network traffic. It includes util-linux, uClibc, and BusyBox. All the components have been optimized for home routers." >}}
  {{< card link="router-firmware/index.md#opnsense" title="OPNsense" image="router-firmware/opnsense.svg" subtitle="OPNsense is an open-source, FreeBSD-based firewall and routing platform which incorporates many advanced features such as traffic shaping, load balancing, and VPN capabilities, with many more features available in the form of plugins." >}}
{{< /cards >}}
</div>
