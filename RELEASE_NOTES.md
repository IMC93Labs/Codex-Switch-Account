# Codex Account Switcher v1.7.2

[English](#english) · [Español](#español)

---

<a id="english"></a>
## English

### Main changes

- Credit balance is displayed using the same rounding criterion as Codex.
- The application avoids opening a second instance and activates the window that is already running.

### Fixes

- Fixed the cents discrepancy caused by converting internal fractional credits directly to euros.

### Behaviour changes

- Opening `v1.7.2` again displays the existing instance instead of creating another window.

### Required migrations

No migration is required. If older instances are still open, close them once and use the `v1.7.2` executable.

### Known issues

- Older versions that are already running cannot adopt single-instance control; they must be closed manually once.

---

<a id="español"></a>
## Español

### Novedades principales

- El saldo de créditos se muestra con el mismo criterio de redondeo que Codex.
- La aplicación evita abrir una segunda instancia y activa la ventana que ya está en ejecución.

### Correcciones

- Se corrige la discrepancia de céntimos causada por convertir fracciones internas de crédito directamente a euros.

### Cambios de comportamiento

- Al abrir `v1.7.2` de nuevo, se muestra la instancia existente en vez de crear otra ventana.

### Migraciones necesarias

No se requiere ninguna migración. Si siguen abiertas instancias antiguas, ciérralas una vez y usa el ejecutable `v1.7.2`.

### Problemas conocidos

- Las versiones anteriores que ya estaban abiertas no pueden adoptar el control de instancia única; deben cerrarse manualmente una vez.
