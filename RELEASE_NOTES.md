# Codex Account Switcher v1.7.2

## Novedades principales

- El saldo de créditos se muestra con el mismo criterio de redondeo que Codex.
- La aplicación evita abrir una segunda instancia y activa la ventana que ya está en ejecución.

## Correcciones

- Se corrige la discrepancia de céntimos causada por convertir fracciones internas de crédito directamente a euros.

## Cambios de comportamiento

- Al abrir `v1.7.2` de nuevo, se muestra la instancia existente en vez de crear otra ventana.

## Migraciones necesarias

No se requiere ninguna migración. Si siguen abiertas instancias antiguas, ciérralas una vez y usa el ejecutable `v1.7.2`.

## Problemas conocidos

- Las versiones anteriores que ya estaban abiertas no pueden adoptar el control de instancia única; deben cerrarse manualmente una vez.
