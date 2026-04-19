<div align="center">

# `.github`

### Repositorio de configuracion de la organizacion DO Cacao

[![Organization Profile](https://img.shields.io/badge/Ver-Perfil_de_la_Organizaci%C3%B3n-8D6E63?style=for-the-badge&logo=github&logoColor=white)](https://github.com/do-cacao-workspace)

</div>

---

## Que es este repositorio?

Este es el repositorio especial **`.github`** de la organizacion [DO Cacao](https://github.com/do-cacao-workspace). En GitHub, el repositorio `.github` cumple un rol especifico a nivel organizacional:

### Funciones principales

| Funcion | Descripcion | Ubicacion |
|:---|:---|:---|
| **Perfil de la organizacion** | Contiene el README que se muestra publicamente en la pagina principal de la organizacion en GitHub | `profile/README.md` |
| **Templates de Issues y PRs** | Plantillas reutilizables para estandarizar la creacion de issues y pull requests en todos los repositorios | `ISSUE_TEMPLATE/`, `PULL_REQUEST_TEMPLATE.md` |
| **Workflows compartidos** | GitHub Actions reutilizables que pueden ser referenciados desde cualquier repositorio de la organizacion | `workflow-templates/` |
| **Configuracion de comunidad** | Archivos como `CODE_OF_CONDUCT.md`, `CONTRIBUTING.md` y `SECURITY.md` que aplican como defaults para todos los repositorios | Raiz del repositorio |

## Estructura actual

```
.github/
├── profile/
│   └── README.md        # Perfil publico de la organizacion DO Cacao
├── README.md            # Este archivo (documentacion del repositorio)
└── .gitignore
```

## Perfil de la organizacion

El archivo [`profile/README.md`](./profile/README.md) contiene la presentacion publica de **DO Cacao** — la plataforma digital B2B orientada a la trazabilidad, gestion operativa y comercializacion del cacao con denominacion de origen.

Este README se renderiza automaticamente en la pagina principal de la organizacion en GitHub y sirve como carta de presentacion para visitantes, colaboradores potenciales y cualquier persona interesada en el proyecto.

**Para ver el perfil en accion**, visita la [pagina de la organizacion en GitHub](https://github.com/do-cacao-workspace).

## Como contribuir a este repositorio

Si necesitas modificar el perfil de la organizacion o agregar configuracion compartida:

1. Crea una rama desde `main`
2. Realiza los cambios necesarios
3. Abre un Pull Request con una descripcion clara de los cambios
4. Solicita revision antes de hacer merge

---

<div align="center">

<sub>DO Cacao — Trazabilidad, Gestion y Confianza para el ecosistema cacaotero</sub>

</div>
