# Contributing to InHive

Thanks for your interest in improving InHive — a free, open-source VPN client
and proxy core for censorship circumvention.

## Project Layout

InHive is split across several repositories:

| Repo | What |
|------|------|
| [inhive-core](https://github.com/TwilgateLabs/inhive-core) | Go proxy engine (sing-box fork) — builds the library consumed by the apps |
| [inhive-android](https://github.com/TwilgateLabs/inhive-android) / [windows](https://github.com/TwilgateLabs/inhive-windows) / [ios](https://github.com/TwilgateLabs/inhive-ios) / [macos](https://github.com/TwilgateLabs/inhive-macos) | Release binaries + platform notes |
| [utproto](https://github.com/TwilgateLabs/utproto) | Standalone FakeTLS transport library |
| [inhive-rules](https://github.com/TwilgateLabs/inhive-rules) | Compiled `.srs` blocklists |

The client app source lives in a separate product repository; the public app is
distributed via the release mirrors above and at [app.inhive.ru](https://app.inhive.ru).

## How to Contribute

1. **Open an issue first** for anything non-trivial — describe the problem or
   proposal before writing code, so we can align on direction.
2. **Fork and branch** from the default branch.
3. **Keep changes focused** — one logical change per pull request.
4. **Match existing style** — read the surrounding code; consistency over
   personal preference.
5. **Test your change** — describe how you verified it in the PR.

## Reporting Bugs

Use the issue templates. Include your platform, app/core version, and clear
reproduction steps. For VPN connectivity issues, a sanitized log (no secrets,
no real server addresses) helps enormously.

## Security

Do **not** file security vulnerabilities as public issues — see
[SECURITY.md](SECURITY.md).

## License

By contributing, you agree your contributions are licensed under the same
license as the repository you contribute to (GPL-3.0-or-later for the core).
