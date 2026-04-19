<div align="center">

# `.github`

### Repositorio de configuración de la organización DO Cacao

[![Organization Profile](https://img.shields.io/badge/Ver-Perfil_de_la_Organizaci%C3%B3n-8D6E63?style=for-the-badge&logo=github&logoColor=white)](https://github.com/do-cacao-workspace)

</div>

---

## Qué es este repositorio?

Este es el repositorio especial **`.github`** de la organización [DO Cacao](https://github.com/Docacao). En GitHub, el repositorio `.github` cumple un rol específico a nivel organizacional:

### Funciones principales

| Función | Descripción | Ubicación |
|:---|:---|:---|
| **Perfil de la organización** | Contiene el README que se muestra públicamente en la página principal de la organización en GitHub | `profile/README.md` |
| **Templates de Issues y PRs** | Plantillas reutilizables para estandarizar la creación de issues y pull requests en todos los repositorios | `ISSUE_TEMPLATE/`, `PULL_REQUEST_TEMPLATE.md` |
| **Workflows compartidos** | GitHub Actions reutilizables que pueden ser referenciados desde cualquier repositorio de la organización | `workflow-templates/` |
| **Configuración de comunidad** | Archivos como `CODE_OF_CONDUCT.md`, `CONTRIBUTING.md` y `SECURITY.md` que aplican como defaults para todos los repositorios | Raíz del repositorio |

## Estructura actual

```
.github/
├── profile/
│   └── README.md        # Perfil público de la organización DO Cacao
├── README.md            # Este archivo (documentación del repositorio)
└── .gitignore
```

## Perfil de la organización

El archivo [`profile/README.md`](./profile/README.md) contiene la presentación pública de **DO Cacao** — la plataforma digital B2B orientada a la trazabilidad, gestión operativa y comercialización del cacao con denominación de origen.

Este README se renderiza automáticamente en la página principal de la organización en GitHub y sirve como carta de presentación para visitantes, colaboradores potenciales y cualquier persona interesada en el proyecto.

**Para ver el perfil en acción**, visita la [página de la organización en GitHub](https://github.com/Docacao).

## Cómo contribuir a este repositorio

Si necesitas modificar el perfil de la organización o agregar configuración compartida:

1. Crea una rama desde `main`
2. Realiza los cambios necesarios
3. Abre un Pull Request con una descripción clara de los cambios
4. Solicita revisión antes de hacer merge

---

<div align="center">

<sub>DO Cacao — Trazabilidad, Gestión y Confianza para el ecosistema cacaotero</sub>

</div>
