---
title: Self-Hosting
description: For our more technical readers, self-hosting software and services can provide additional privacy assurances since you have maximum control over your data.
weight: 60
---
<small>Protects against the following threat(s):</small>

[{{< badge content="Service Providers" color="indigo" >}}](../../wiki/basics/common-threats.md#privacy-from-service-providers)

**Self-hosting** software and services can be a way to achieve a higher level of privacy through digital sovereignty, particularly independence from cloud servers controlled by product developers or vendors. By self-hosting, we mean hosting applications and data on your own hardware.

Self-hosting your own solutions requires advanced technical knowledge and a deep understanding of the associated risks. By becoming the host for yourself and possibly others, you take on responsibilities you might not otherwise have. Self-hosting privacy software improperly can leave you worse off than using e.g. an end-to-end encrypted service provider, so it is best avoided if you are not already comfortable doing so.

## DNS Filtering

<div class="pg-card-logos">
{{< cards >}}
  {{< card link="dns-filtering/_index.md#adguard-home" title="AdGuard Home" image="dns-filtering/adguard-home.svg" subtitle="AdGuard Home is an open-source DNS sinkhole which features a polished web interface to view insights and manage blocked content." >}}
  {{< card link="dns-filtering/_index.md#pi-hole" title="Pi-hole" image="dns-filtering/pi-hole.svg" subtitle="Pi-hole is an open-source DNS sinkhole which features a friendly web interface to view insights and manage blocked content. Pi-hole is designed to be hosted on a Raspberry Pi, but it is not limited to such hardware." >}}
{{< /cards >}}
</div>

## Email Servers

<div class="pg-card-logos">
{{< cards >}}
  {{< card link="email-servers/_index.md#stalwart" title="Stalwart" image="email-servers/stalwart.svg" subtitle="Stalwart is a newer mail server written in Rust which supports JMAP in addition to the standard IMAP, POP3, and SMTP. It has a wide variety of configuration options, but also defaults to very reasonable settings in terms of both security and features, making it easy to use immediately." >}}
  {{< card link="email-servers/_index.md#mailcow" title="Mailcow" image="email-servers/mailcow.svg" subtitle="Mailcow is an advanced mail server perfect for those with Linux experience. It has everything you need in a Docker container: a mail server with DKIM support, antivirus and spam monitoring, webmail and ActiveSync with SOGo, and web-based administration with 2FA support." >}}
  {{< card link="email-servers/_index.md#mail-in-a-box" title="Mail-in-a-Box" image="email-servers/mail-in-a-box.svg" subtitle="Mail-in-a-Box is an automated setup script for deploying a mail server on Ubuntu. Its goal is to make it easier for people to set up their own mail server." >}}
{{< /cards >}}
</div>

## File Management

<div class="pg-card-logos">
{{< cards >}}
  {{< card link="file-management/_index.md#photoprism" title="PhotoPrism" image="file-management/photoprism.svg" subtitle="PhotoPrism is a platform for managing photos. It supports album syncing and sharing as well as a variety of other features. It does not include end-to-end encryption, so it’s best hosted on a server that you trust and is under your control." >}}
  {{< card link="file-management/_index.md#freedombox" title="FreedomBox" image="file-management/freedombox.svg" subtitle="FreedomBox is an operating system designed to be run on a single-board computer (SBC). The purpose is to make it easy to set up server applications for use cases like sharing files." >}}
  {{< card link="file-management/_index.md#nextcloud" title="Nextcloud" image="file-management/nextcloud.svg" subtitle="Nextcloud is a suite of free and open-source client-server software for creating your own file hosting services on a private server you control." >}}
{{< /cards >}}
</div>

## Password Sync

<div class="pg-card-logos">
{{< cards >}}
  {{< card link="passwords/_index.md#vaultwarden" title="Vaultwarden" image="passwords/vaultwarden.svg" subtitle="Vaultwarden is an alternative implementation of Bitwarden's sync server written in Rust and compatible with official Bitwarden clients, perfect for self-hosted deployment where running the resource-heavy, official service might not be ideal." >}}
{{< /cards >}}
</div>

## More Tools

These recommendations live in other tools categories (software and services) but also support self-hosting when you are comfortable operating them yourself.

<div class="pg-card-logos">
{{< cards >}}
  {{< card link="../services/cloud/_index.md#peergos" title="Peergos" image="../services/cloud/peergos.svg" subtitle="Peergos is a decentralized protocol and open-source platform for storage, social media, and applications. It provides a secure and private space where users can store, share, view, and edit their photos, videos, documents, etc." >}}
  {{< card link="../services/email-aliasing/_index.md#addyio" title="Addy.io" image="../services/email-aliasing/addy.svg" subtitle="Addy.io lets you create 10 domain aliases on a shared domain for free, or unlimited standard aliases. The number of shared aliases (which end in a shared domain like @addy.io) that you can create depends on the plan you are subscribed to." >}}
  {{< card link="../services/email-aliasing/_index.md#simplelogin" title="SimpleLogin" image="../services/email-aliasing/simplelogin.svg" subtitle="SimpleLogin is a free service which provides email aliases on a variety of shared domain names, and optionally provides paid features like unlimited aliases and custom domains." >}}
  {{< card link="../services/messengers/_index.md#simplex-chat" title="SimpleX Chat" image="../services/messengers/simplex.svg" subtitle="SimpleX Chat is an instant messenger that doesn't depend on any unique identifiers such as phone numbers or usernames. Its decentralized network makes SimpleX Chat an effective tool against censorship." >}}
  {{< card link="../services/photo-backups/_index.md#ente-photos" title="Ente Photos" image="../services/photo-backups/ente.svg" subtitle="Ente Photos is an end-to-end encrypted photo backup service which supports automatic backups on iOS and Android. Their code is fully open source, both on the client side and on the server side." >}}
  {{< card link="../software/document-collaboration/_index.md#cryptpad" title="CryptPad" image="../software/document-collaboration/cryptpad.svg" subtitle="CryptPad is a private-by-design alternative to popular, full-fledged office suites. All content on this web service is E2EE and can be shared with other users easily." >}}
  {{< card link="../software/file-sharing/_index.md#send" title="Send" image="../software/file-sharing/send.svg" subtitle="Send is a fork of Mozilla's discontinued Firefox Send service which allows you to send files to others with a link. Files are encrypted on your device so that they cannot be read by the server, and they can be optionally password-protected as well." >}}
  {{< card link="../software/frontends/_index.md#invidious" title="Invidious" image="../software/frontends/invidious.svg" subtitle="Invidious is a free and open-source frontend for YouTube that is also self-hostable." >}}
  {{< card link="../software/frontends/_index.md#piped" title="Piped" image="../software/frontends/piped.svg" subtitle="Piped is a free and open-source frontend for YouTube that is also self-hostable." >}}
  {{< card link="../software/frontends/_index.md#proxitok" title="ProxiTok" image="../software/frontends/proxitok.svg" subtitle="ProxiTok is an open-source frontend to the TikTok website that is also self-hostable." >}}
  {{< card link="../software/frontends/_index.md#redlib" title="Redlib" image="../software/frontends/redlib.svg" subtitle="Redlib is an open-source frontend to the Reddit website that is also self-hostable. You can access Redlib through a number of public instances." >}}
  {{< card link="../software/language-tools/_index.md#libretranslate" title="LibreTranslate" image="../software/language-tools/libretranslate.png" subtitle="LibreTranslate is a free and open-source machine translation web interface and API server. It uses Argos Translate models on the backend for translations." >}}
  {{< card link="../software/news-aggregators/_index.md#miniflux" title="Miniflux" image="../software/news-aggregators/miniflux.svg" subtitle="Miniflux is a web-based news aggregator that you can self-host." >}}
  {{< card link="../software/notebooks/_index.md#standard-notes" title="Standard Notes" image="../software/notebooks/standard-notes.svg" subtitle="Standard Notes is a simple and private notes app that features cross-platform sync for seamless use. It features E2EE on every platform, and a powerful desktop experience with themes and custom editors." >}}
  {{< card link="../software/pastebins/_index.md#paaster" title="Paaster" image="../software/pastebins/paaster.svg" subtitle="Paaster is a secure and user-friendly pastebin application that prioritizes privacy and simplicity. With end-to-end encryption and paste history, Paaster ensures that your pasted code remains confidential and accessible." >}}
  {{< card link="../software/pastebins/_index.md#privatebin" title="PrivateBin" image="../software/pastebins/privatebin.svg" subtitle="PrivateBin is a minimalist, open-source, online pastebin where the server cannot decrypt and read any pasted data you submit. Data is encrypted/decrypted in the browser using 256-bit AES." >}}
  {{< card link="../software/social-networks/_index.md#element" title="Element" image="../software/social-networks/element.svg" subtitle="Element is the flagship client for the Matrix protocol, an open standard that enables decentralized communication by way of federated chat rooms. Users can exist on different homeservers but still communicate with each other." >}}
  {{< card link="../software/social-networks/_index.md#mastodon" title="Mastodon" image="../software/social-networks/mastodon.svg" subtitle="Mastodon is a social network based on open web protocols and free, open-source software. It uses the ActivityPub protocol, which is decentralized like email: Users can exist on different servers or even different platforms but still communicate with each other." >}}
{{< /cards >}}
</div>
