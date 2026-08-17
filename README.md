<div align="center">

# Codex Account Switcher

**Manage and switch between multiple Codex Desktop accounts from one Windows application.**  
**Gestiona y cambia entre varias cuentas de Codex Desktop desde una sola aplicación para Windows.**

`Windows 10/11` · `.NET 8` · `x64` · `OneFile` · `Self-contained`

[**English**](#english) · [**Español**](#español)

[**Latest release / Última versión**](../../releases/latest) · [Support / Soporte](SUPPORT.md) · [Security / Seguridad](SECURITY.md) · [Changelog / Cambios](CHANGELOG.md)

</div>

> [!IMPORTANT]
> **Recommended download / Descarga recomendada:** open the latest **Release** and download `CodexAccountSwitcher.exe`. No installation is required.  
> Abre la última **Release** y descarga `CodexAccountSwitcher.exe`. No necesita instalación.

> [!NOTE]
> Independent **IMC93Labs** project. It is not affiliated with, endorsed by, or sponsored by OpenAI.  
> Proyecto independiente de **IMC93Labs**. No está afiliado, respaldado ni patrocinado por OpenAI.

---

<a id="english"></a>
# English

## What it does

Codex Account Switcher provides a compact interface for the legitimate use of multiple **Codex Desktop** accounts that you own or are authorized to use.

- Store up to **8 accounts** locally.
- Quickly switch accounts manually, with no automatic quota balancing or rotation.
- Read usage limits and reset windows when Codex reports them.
- Display available balance/credits when provided by Codex.
- Open and control Codex Desktop from the utility.
- Periodically refresh account information.
- System tray integration and optional Windows startup.
- Encrypted backups of accounts, local history and complete PC-to-PC migration.
- Integrated updater using the official Releases from this repository.

## Demo screenshots

The screenshots below reproduce the application interface using **completely fictional accounts and data**. They do not contain the developer's real email addresses, tokens or private information.

### Main window

![Codex Account Switcher - main window with demo data](assets/screenshots/main-demo.svg)

<table>
<tr>
<td width="50%" valign="top"><b>About</b><br><br><img src="assets/screenshots/about-demo.svg" alt="About window" width="100%"></td>
<td width="50%" valign="top"><b>Settings and migration</b><br><br><img src="assets/screenshots/settings-demo.svg" alt="Settings window" width="100%"></td>
</tr>
</table>

## Download and integrity

Official builds are published only through **[GitHub Releases](../../releases)**.

1. Download `CodexAccountSwitcher.exe` from the latest Release.
2. To verify the download, compare its SHA-256 hash with `SHA256SUMS.txt`.
3. `RELEASE_MANIFEST.json` records the version, architecture, build information, tests and warnings for each release.
4. `update.json` is used by the application's integrated updater.

The published executable is **Windows x64, self-contained and OneFile**, so a separate .NET installation is not required.

### About “Source code (zip)” and “Source code (tar.gz)”

GitHub automatically generates these two downloads for every tag. In this repository they contain **only the public documentation and release metadata stored in this Releases repository**; they **do not contain the Codex Account Switcher application source code**.

## Privacy and security

- The application source code is **not published in this repository**.
- Credentials and session information must not be posted in Issues, screenshots or logs.
- Portable backups created by the application are encrypted with a password chosen by the user.
- Sensitive local data is protected again with Windows DPAPI when restored for the destination Windows user.
- Read [SECURITY.md](SECURITY.md) before publicly reporting a security-sensitive issue.

## Responsible use

The tool does not create accounts, combine subscriptions, merge quotas or attempt to bypass service limits, billing, authentication or access controls. Users are responsible for using only accounts they own or are authorized to access and for complying with the applicable service terms.

## Support

- **Bugs:** Issues → `Report a bug / Reportar un problema`.
- **Improvements:** Issues → `Request an improvement / Solicitar una mejora`.
- **General help:** Discussions.
- **Security:** [SECURITY.md](SECURITY.md).
- **Full support guide:** [SUPPORT.md](SUPPORT.md).

## Notice

Codex Account Switcher is a personal IMC93Labs project developed with the assistance of AI tools. It is provided **as-is and without warranty**; keep appropriate backups of important data. See [DISCLAIMER.md](DISCLAIMER.md) for the full notice.

<p align="right"><a href="#codex-account-switcher">↑ Back to top</a></p>

---

<a id="español"></a>
# Español

## Qué hace

Codex Account Switcher centraliza en una interfaz compacta el uso legítimo de varias cuentas propias o autorizadas de **Codex Desktop**.

- Hasta **8 cuentas** guardadas localmente.
- Cambio manual rápido entre cuentas, sin balanceo ni rotación automática de límites.
- Lectura de límites de uso y ventanas de reinicio cuando Codex los informa.
- Visualización de saldo/créditos cuando están disponibles.
- Apertura y control de Codex Desktop desde la utilidad.
- Actualización periódica de la información de las cuentas.
- Bandeja del sistema y arranque con Windows.
- Copias cifradas de cuentas, historial local y migración completa entre equipos.
- Actualizador integrado desde las Releases oficiales de este repositorio.

## Capturas de demostración

Las imágenes siguientes reproducen la interfaz de la aplicación con **cuentas y datos completamente ficticios**. No contienen correos, tokens ni información privada del desarrollador.

### Ventana principal

![Codex Account Switcher - ventana principal con datos demo](assets/screenshots/main-demo.svg)

<table>
<tr>
<td width="50%" valign="top"><b>Acerca de</b><br><br><img src="assets/screenshots/about-demo.svg" alt="Ventana Acerca de" width="100%"></td>
<td width="50%" valign="top"><b>Ajustes y migración</b><br><br><img src="assets/screenshots/settings-demo.svg" alt="Ventana Ajustes" width="100%"></td>
</tr>
</table>

## Descarga e integridad

Las versiones oficiales se publican únicamente en **[GitHub Releases](../../releases)**.

1. Descarga `CodexAccountSwitcher.exe` de la última Release.
2. Si quieres verificar el archivo, compara su SHA-256 con `SHA256SUMS.txt`.
3. `RELEASE_MANIFEST.json` documenta versión, arquitectura, build, pruebas y advertencias de cada publicación.
4. `update.json` es utilizado por el actualizador integrado de la aplicación.

El ejecutable publicado es **Windows x64, self-contained y OneFile**, por lo que no requiere instalar .NET por separado.

### Sobre “Source code (zip)” y “Source code (tar.gz)”

GitHub genera automáticamente esos dos enlaces para cada tag. En este repositorio contienen **solo la documentación y metadatos públicos del repositorio de Releases**; **no contienen el código fuente de Codex Account Switcher**.

## Privacidad y seguridad

- El código fuente de la aplicación **no se publica en este repositorio**.
- Las credenciales y sesiones no deben publicarse en Issues, capturas ni registros.
- Las copias portátiles creadas por la aplicación se protegen con la contraseña elegida por el usuario.
- Los datos locales sensibles se vuelven a proteger con DPAPI al restaurarlos en el usuario de Windows de destino.
- Consulta [SECURITY.md](SECURITY.md) antes de informar públicamente de un problema sensible.

## Uso responsable

La herramienta no crea cuentas, no combina suscripciones, no suma cuotas entre cuentas y no está diseñada para eludir límites, facturación, autenticación ni controles de acceso. Cada usuario es responsable de utilizar únicamente cuentas que le pertenezcan o que esté autorizado a usar y de cumplir las condiciones aplicables al servicio.

## Soporte

- **Errores:** Issues → `Report a bug / Reportar un problema`.
- **Mejoras:** Issues → `Request an improvement / Solicitar una mejora`.
- **Ayuda general:** Discussions.
- **Seguridad:** [SECURITY.md](SECURITY.md).
- **Guía completa:** [SUPPORT.md](SUPPORT.md).

## Aviso

Codex Account Switcher es un proyecto personal de IMC93Labs desarrollado con asistencia de herramientas de IA. Se publica **tal cual y sin garantías**; conserva copias de seguridad de cualquier dato importante. Consulta [DISCLAIMER.md](DISCLAIMER.md) para el aviso completo.

<p align="right"><a href="#codex-account-switcher">↑ Volver arriba</a></p>

---

<div align="center"><b>Codex Account Switcher · IMC93Labs</b></div>
