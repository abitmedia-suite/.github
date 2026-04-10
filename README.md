# .github

Repositorio central de configuración: templates de issues, pull requests y lineamientos de contribución compartidos entre todos los repositorios.

## Contenido

### Issue Templates

| Template | Descripción | Tipo |
| --- | --- | --- |
| [Historia de usuario](.github/ISSUE_TEMPLATE/user-story.yml) | Formulario con campos Como/Quiero/Para, criterios de aceptación y prioridad | Feature |
| [Reporte de bug](.github/ISSUE_TEMPLATE/bug-report.yml) | Formulario con pasos para reproducir, resultado esperado/actual, severidad y reproducibilidad | Bug |

### Pull Request Template

| Template | Descripción |
| --- | --- |
| [Pull Request](.github/PULL_REQUEST_TEMPLATE.md) | Estructura estándar con objetivo, cambios realizados, qué probar y rollback |

### Configuración

| Archivo | Descripción |
| --- | --- |
| [config.yml](.github/ISSUE_TEMPLATE/config.yml) | Deshabilita la creación de issues en blanco, obligando el uso de templates |

## Cómo funciona

Los repositorios que no tengan sus propios templates heredan automáticamente los definidos aquí. Si un repositorio define sus propios templates, estos tienen prioridad sobre los compartidos.
