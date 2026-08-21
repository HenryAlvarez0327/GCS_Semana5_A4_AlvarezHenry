\# CM\_STATUS\_REGISTER.md



\## Registro de Estados de Configuración



| EC-ID | Elemento de Configuración | Tipo | Versión/Ref | Estado | Responsable | Evidencia |

|------:|---------------------------|------|-------------|--------|-------------|-----------|

| EC-01 | docs/SRS/SRS\_v1.md | Documento | v1.0.0 / v1.1.0 | Aprobado | Henry Alvarez | Commits 10711d3 y dd08035 + tags |

| EC-02 | src/app.py | Código | v1.0.0 | Baselined | Henry Alvarez | Commit 10711d3 + tag v1.0.0 |

| EC-03 | tests/test\_app.py | Prueba | v1.0.0 | Integrado | Henry Alvarez | Commit 10711d3 + tag v1.0.0 |

| EC-04 | README.md | Documento | v1.0.0 | Baselined | Henry Alvarez | Commit 10711d3 + tag v1.0.0 |

| EC-05 | CHANGELOG.md | Documento | v1.1.1 | Aprobado | Henry Alvarez | Commit b86dbbb + PR #2 |

| EC-06 | .gitignore | Configuración | bfc97ce | Aprobado | Henry Alvarez | Commit bfc97ce + Issue #1 |

| EC-07 | config/.env.example | Configuración | bfc97ce | Integrado | Henry Alvarez | Commit bfc97ce + Issue #1 |

| EC-08 | CM\_STATUS\_REGISTER.md | Documento GCS | main | En revisión | Henry Alvarez | Registro de Status Accounting |



\## Línea base



La línea base v1.0.0 incluye la estructura inicial del repositorio, el documento SRS v1, el código fuente mínimo, la prueba inicial y el README. Esta versión constituye el punto estable de referencia para controlar los cambios posteriores.



\## Trazabilidad



La auditoría permitió relacionar los cambios con commits, tags, el Issue #1 y el Pull Request #2. Los tags incorrectos v1.0 y release-1.1 fueron reemplazados por versiones compatibles con SemVer: v1.0.0, v1.1.0 y v1.1.1.

