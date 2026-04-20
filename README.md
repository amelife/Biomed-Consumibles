# BIOMED MD Consumibles

Sistema de gestión de consumibles ZOLL para BIOMED MD.
**Versión 1.2.0** · 2026-04-20

---

## 📦 Archivos del proyecto

Todos estos archivos van al repo de GitHub Pages (en la raíz):

```
biomedmd-consumibles/
├── index.html                    ← Frontend principal
├── manifest.json                 ← PWA config
├── logo-biomed.png               ← Logo completo (login)
├── isotipo.png                   ← Solo símbolo (topbar)
├── favicon.ico                   ← Multi-tamaño
├── favicon-16x16.png
├── favicon-32x32.png
├── apple-touch-icon.png          ← iOS home screen
├── icon-192.png                  ← PWA Android
└── icon-512.png                  ← PWA splash
```

Y en el editor de Apps Script:
```
Code.gs                           ← Backend completo
```

---

## 🎯 Features v1.2

- ✅ Login con desplegable de usuarios + PIN
- ✅ Logo BIOMED MD integrado en login y topbar
- ✅ PWA instalable (agregar a inicio en iOS/Android)
- ✅ Favicon multi-tamaño
- ✅ 4 productos ZOLL con vida útil automática
- ✅ Gestión jerárquica Clientes → Equipos → Consumibles
- ✅ Stock BIOMED MD con ingresos/egresos
- ✅ Historial completo de cambios
- ✅ Alertas email a 90/60/30/15/7 días + vencidos
- ✅ Dashboard con KPIs y gráfico 12 meses

---

## 📱 Agregar a inicio del celular

### iPhone (Safari)
1. Abrir la URL en Safari
2. Botón compartir (↑) → "Agregar a pantalla de inicio"

### Android (Chrome)
1. Abrir la URL en Chrome
2. Menú (⋮) → "Instalar app"

Se comporta como app nativa sin barra de navegador.

---

## 🚀 Deploy

### GitHub Pages
1. Crear repo `biomedmd-consumibles` (público)
2. Subir todos los archivos listados arriba a la raíz
3. Settings → Pages → Branch `main` / root
4. Esperar 1-2 min → URL: `https://TU-USUARIO.github.io/biomedmd-consumibles/`

### Apps Script (ya configurado)
URL actual: `https://script.google.com/macros/s/AKfycbzA80vWb85nJM2U0QMmXdgRZNllCEC3Ppz25wneH4F1IrRIsfXwXe0gUnIPbxCoOGDgdw/exec`

Para actualizar Code.gs: Implementar → Administrar implementaciones → ✏️ → Nueva versión → Implementar.

---

## 👥 Usuarios

Los 4 admins ya están cargados en el Sheet con PIN `1234`:
- Daniel · Ezequiel · Johana · Germán

Editable en la hoja **Admins** del Sheet "BIOMED MD Consumibles DB".

---

## 📦 Catálogo ZOLL

| Código | Producto | Vida útil |
|---|---|---|
| `8900-0800-01` | 🫀 CPR-D-padz® adulto | 5 años |
| `8900-0810-01` | 👶 Pedi-padz® II pediátrico | 2 años |
| `8900-0400` | ⚡ CPR Stat-padz HVP | 2 años |
| `8000-0807-01` | 🔋 Pack baterías Type 123 Lithium | 5 años |
