# Proyecto 10: Extractor de documentación de IaC y diagramador básico

**Alumno:** Alanya Campos, Luis Alberto

**Código:** 20210290J

**Correo:** luis.alanya.c@uni.pe

**Repositorio del Proyecto:** [https://github.com/Jharvichu/PC4_Grupo8_Proyecto10](https://github.com/Jharvichu/PC4_Grupo8_Proyecto10)

### Rol en el equipo

Para este proyecto, me encargué de la creación de algunas *issues* para cada *sprint*, como también de la elaboración de guías informativas para la buena elaboración de ramas y *commits*. Contribuí al desarrollo de los tests, tanto de los scripts `python` como de los módulos `terraform`. Implementé también los tres *hooks* que usamos durante el proyecto (`pre-commit`, `msg-commit` y `pre-push`) como también el *script* `setup.sh` que crea el entorno de trabajo.

### Instrucciones

Todos los comandos funcionan únicamente en sistemas basados en Linux, como Ubuntu, Debian, Fedora, etc.

```bash
$ git clone https://github.com/AlbeCamp21/mi_proyecto_individual.git
$ cd mi_proyecto_individual
# Entrando al entorno de trabajo
$ source setup.sh
# Probar hooks (pre-commit y pre-push)
$ ./.git/hooks/pre-commit
$ ./.git/hooks/pre-push 
```
