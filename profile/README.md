<div align="center">
  <img src="https://raw.githubusercontent.com/TwilgateLabs/.github/main/assets/logo.png" width="120" alt="InHive">
  <h1>InHive — Next-gen VPN Client</h1>
  <p><strong>Modern VPN protocols. Built for privacy.</strong></p>
  <p>
    <a href="https://app.inhive.ru"><img src="https://img.shields.io/badge/Website-app.inhive.ru-F2B454?style=flat-square" alt="Website"></a>
    <a href="https://t.me/InHive_support_bot"><img src="https://img.shields.io/badge/Telegram-support-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram"></a>
  </p>
</div>

## 📥 Downloads

<table>
  <thead>
    <tr><th>OS</th><th>Download</th></tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Android</strong></td>
      <td>
        <a href="https://github.com/TwilgateLabs/inhive-android/releases/latest"><img src="https://img.shields.io/badge/APK-Universal-044d29?style=flat-square&logo=android&logoColor=white" alt="APK"></a>
        <a href="https://github.com/TwilgateLabs/inhive-android/releases"><img src="https://img.shields.io/badge/Beta-Pre--release-7c4dff?style=flat-square&logo=android&logoColor=white" alt="Beta"></a>
      </td>
    </tr>
    <tr>
      <td><strong>iOS</strong></td>
      <td>
        <a href="https://github.com/TwilgateLabs/inhive-ios"><img src="https://img.shields.io/badge/TestFlight-Beta-1976d2?style=flat-square&logo=apple&logoColor=white" alt="TestFlight"></a>
        <a href="https://github.com/TwilgateLabs/inhive-ios"><img src="https://img.shields.io/badge/App_Store-Soon-9e9e9e?style=flat-square&logo=apple&logoColor=white" alt="App Store"></a>
      </td>
    </tr>
    <tr>
      <td><strong>Windows</strong></td>
      <td>
        <a href="https://github.com/TwilgateLabs/inhive-windows/releases/latest"><img src="https://img.shields.io/badge/Setup-x64-2d7d9a?style=flat-square&logo=windows&logoColor=white" alt="Windows x64"></a>
        <a href="https://github.com/TwilgateLabs/inhive-windows/releases/latest"><img src="https://img.shields.io/badge/Portable-zip-2d7d9a?style=flat-square&logo=windows&logoColor=white" alt="Portable"></a>
      </td>
    </tr>
    <tr>
      <td><strong>macOS</strong></td>
      <td>
        <a href="https://github.com/TwilgateLabs/inhive-macos"><img src="https://img.shields.io/badge/DMG-Soon-9e9e9e?style=flat-square&logo=apple&logoColor=white" alt="macOS"></a>
        <a href="https://github.com/TwilgateLabs/inhive-macos"><img src="https://img.shields.io/badge/Mac_App_Store-Soon-9e9e9e?style=flat-square&logo=apple&logoColor=white" alt="MAS"></a>
      </td>
    </tr>
    <tr>
      <td><strong>Linux</strong></td>
      <td>
        <img src="https://img.shields.io/badge/Planned-v1.X-9e9e9e?style=flat-square&logo=linux&logoColor=white" alt="Linux">
      </td>
    </tr>
  </tbody>
</table>

## 🌐 Links

- **Website:** [app.inhive.ru](https://app.inhive.ru)
- **Documentation:** [Developer Docs](https://app.inhive.ru/#/dev)
- **FAQ:** [Frequently Asked Questions](https://app.inhive.ru/#/faq)
- **Privacy Policy:** [Privacy](https://app.inhive.ru/#/privacy)
- **Support:** [@InHive_support_bot](https://t.me/InHive_support_bot)

## 🔌 Supported protocols

VLESS (Reality / XHTTP / XTLS-Vision), VMess, Trojan, Shadowsocks, NaiveProxy, Hysteria2, TUIC, WireGuard, AmneziaWG, Mieru, DNSTT, SSH

## 📦 Open-source components

**Core**

- [inhive-core](https://github.com/TwilgateLabs/inhive-core) — Go proxy core, high-performance engine that powers the apps
- [inhive-sing-box](https://github.com/TwilgateLabs/inhive-sing-box) — our sing-box fork with WARP, Psiphon, XHTTP, AmneziaWG patches
- [utproto](https://github.com/TwilgateLabs/utproto) — FakeTLS transport with MTProto-style wire mimicry, standalone Go module
- [inhive-ray2sing](https://github.com/TwilgateLabs/inhive-ray2sing) — V2Ray / Xray config converter to sing-box format

**Rule sets & configs**

- [inhive-rules](https://github.com/TwilgateLabs/inhive-rules) — geosite / geoip rule sets, auto-rebuilt every 6 hours
- [inhive-public-config](https://github.com/TwilgateLabs/inhive-public-config) — public bootstrap config mirror for DPI-blocked regions

**Transport dependency forks**

- [inhive-wireguard-go](https://github.com/TwilgateLabs/inhive-wireguard-go) — WireGuard-Go fork
- [inhive-sing-dns](https://github.com/TwilgateLabs/inhive-sing-dns) — extended DNS library for sing-box
- [inhive-psiphon-quic-go](https://github.com/TwilgateLabs/inhive-psiphon-quic-go) — Psiphon's QUIC fork
- [inhive-psiphon-tls](https://github.com/TwilgateLabs/inhive-psiphon-tls) — Psiphon's TLS fork
- [inhive-tailscale](https://github.com/TwilgateLabs/inhive-tailscale) — Tailscale fork (WireGuard pieces)

## ⚖️ Legal

InHive is a free, client-side VPN utility. We do not run VPN servers. Users bring their own subscription URL. See [Terms](https://app.inhive.ru/#/terms) and [Privacy Policy](https://app.inhive.ru/#/privacy).
