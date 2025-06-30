
# Contribuciones de Luis Alanya

## Sprint 1

- 2025-06-22: Se crea la estructura inicial del repositorio, incluyendo archivos base para documentación, módulos terraform, scripts y tests en Python, además de hooks de git.

  Commits:
  - `docs(readme): (Issue #1) añadir README, .gitignore y requirements inicial` (`c96c28c`)
  - `docs(docs): (Issue #1) añadir estructura base de documentación y sprints` (`5647e38`)
  - `feat(modules): (Issue #1) crear directorio base de módulos terraform` (`7346d83`)
  - `feat(py): (Issue #1) agrager carpetas y archivos iniciales para scripts y tests python` (`1a20015`)
  - `ci(hook): (Issue #1) agregar archivos hooks git iniciales` (`a60d36c`)

  Pull request grupal: [#6](https://github.com/Jharvichu/PC4_Grupo8_Proyecto10/pull/6)

- 2025-06-22: Se agregan y actualizan configuraciones y documentación relacionadas a los hooks (`pre-commit`, `pre-push`, `commit-msg`), así como ajustes en herramientas de linting y coverage.

  Commits:
  -   `feat(py): (Issue #7) agregar configuración base de flake8 y pytest` (`b0c8bdf`)
  -   `feat(hook): (Issue #7) añadir funcionalidad a los hooks pre-commit, pre-push y commit-msg` (`e6ef2e1`)
  -   `chore(tools): (Issue #7) actualizar requirements para linters y coverage` (`2ac4776`)
  -   `docs(readme): (Issue #7) añadir documentación sobre los hooks agregados` (`46ca3b9`)

  Pull request grupal: [#8](https://github.com/Jharvichu/PC4_Grupo8_Proyecto10/pull/8)

- 2025-06-23: Se agrega el script `setup.sh` para crear el entorno de trabajo y se documenta su uso en el README.

  Commits:
  - `feat(sh): (Issue #5) agregar script setup.sh para crear entorno de trabajo` (`5ac0b61`)
  - `docs(readme): (Issue #5) documentar uso de setup.sh en README` (`d3c2ce4`)

  Pull request grupal: [#9](https://github.com/Jharvichu/PC4_Grupo8_Proyecto10/pull/9)

- 2025-06-26: Se eliminan archivos y carpetas relacionadas con Terraform que ahora se encuentran dentro de la carpeta `infra/`.

  Commits:
  - `fix(tf): (Issue #2) eliminar main.tf del proyecto ya que se incorpora en infra/` (`52e607e`)
  - `fix(tf): (Issue #2) eliminar carpeta modules/ del proyecto ya que se incorpora en infra/` (`d7e158f`)

  Pull request grupal: [#17](https://github.com/Jharvichu/PC4_Grupo8_Proyecto10/pull/17)

## Sprint 2

- 2025-06-28: Se agregan y documentan tests para los scripts `doc_extractor.py` y `diagram_generator.py` en el entorno de Python, cubriendo funciones clave, variables y outputs, así como explicaciones detalladas de los tests realizados.

  Commits:
  - `feat(py): (Issue #16) agregar tests para funciones variables y outputs de doc_extractor.py` (`369597c`)
  - `feat(py): (Issue #16) agregar tests para funciones readme, build, write  de doc_extractor.py` (`5c4641a`)
  - `feat(py): (Issue #16) agregar tests para funciones de diagram_generator.py` (`480b651`)
  - `docs(sprint02): (Issue #16) documentar explicación de los tests creados para los scripts` (`88d63cd`)

  Pull request grupal: [#21](https://github.com/Jharvichu/PC4_Grupo8_Proyecto10/pull/21)

## Sprint 3

- 2025-06-29: Se agrega el tests `test_terraform_docs_validate.py` para las pruebas con la documentación generada. Se documenta dicho script y también se realizan modificaciones a `diagram_generator.py` para pasar linting.

  Commits:
  - `fix(py): (Issue #23) modificar archivo para pasar prueba de linting flake8` (`97d8126`)
  - `feat(py): (Issue #23) añadir archivo test_terraform_docs_validation para testing de outputs de documentación generada` (`8b4d56b`)
  - `docs(test): (Issue #23) añadir documentación del script test_terraform_docs_validation` (`5a921f9`)

  Pull request grupal: [#27](https://github.com/Jharvichu/PC4_Grupo8_Proyecto10/pull/27)
