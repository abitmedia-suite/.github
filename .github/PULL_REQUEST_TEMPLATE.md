**Objetivo**:

### Cambios realizados

- [ ] Cambio 1
- [ ] Cambio 2

### Qué probar

- [ ] Verificación 1
- [ ] Verificación 2

### Rollback

#### Sin haber hecho merge

- Cerrar el pull request con `Close pull request`

#### En caso de haber aceptado el merge

- Revertir el merge: `git revert -m 1 <SHA-1 del commit de merge>`
- Hacer push del nuevo commit a la rama correspondiente: `git push origin main` o `git push origin dev`
