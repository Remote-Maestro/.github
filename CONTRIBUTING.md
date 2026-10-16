# Contribuer à Remote Maestro

Merci de votre contribution ! Les conventions complètes sont dans le repo
[`maestro-workspace`](https://github.com/Remote-Maestro/maestro-workspace/tree/main/docs/conventions).

## En bref

1. Ouvrez ou choisissez une **issue** (templates : bug, fonctionnalité, matériel).
2. Créez une branche courte depuis `main` : `feat/…`, `fix/…`, `hw/…`, `docs/…`, `chore/…`.
3. Commits au format **Conventional Commits**, en anglais : `fix(ble): retry pairing on timeout`.
4. Ouvrez une **Pull Request** (description en français, template fourni), liez l'issue (`Closes #12`).
5. CI verte + revue → **squash merge**. Le titre de la PR devient le message de commit.

## Matériel

- Fichiers binaires (STEP, STL, PDF…) via **Git LFS**.
- Sorties de fabrication générées en CI, jamais committées à la main.
- ERC/DRC propres avant tout tag de révision (`rev-A`, `rev-B`…).

## Claude Code

Les repos contiennent des `CLAUDE.md` décrivant commandes et conventions. Sur une issue ou une PR,
mentionnez `@claude` pour solliciter une analyse, une implémentation ou une revue.
