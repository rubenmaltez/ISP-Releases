# SITECSA CRM — Releases & Actualizaciones

Repositorio público para la distribución de instaladores y actualizaciones de **SITECSA CRM**.

---

## Instalación en Windows (PC)

Para instalar o actualizar en una máquina Windows con un solo comando:

1. Abre **PowerShell como Administrador** (clic derecho → *Ejecutar como administrador*).
2. Ejecuta el siguiente comando:

```powershell
irm https://github.com/rubenmaltez/ISP-Releases/releases/latest/download/install-sitecsa.ps1 | iex
```

*(El script descarga la última versión del paquete MSIX, confía el certificado de instalación y despliega la aplicación automáticamente en el menú Inicio).*

---

## Instalación en Android

1. Descarga el archivo `SITECSA-CRM.apk` desde la sección de **[Releases](https://github.com/rubenmaltez/ISP-Releases/releases/latest)**.
2. Abre el archivo en tu dispositivo Android y permite la instalación de orígenes desconocidos si el sistema lo solicita.
3. Presiona **Instalar** (o **Actualizar** si ya la tenías instalada).
