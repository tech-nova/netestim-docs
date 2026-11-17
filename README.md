# Documentation utilisateur Netestim

Sources de la documentation utilisateur, publiée sur https://tech-nova.github.io/netestim-docs/.

Le site est construit avec [MkDocs](https://www.mkdocs.org/) et le thème [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/). Chaque push sur `main` le republie automatiquement (`.github/workflows/deploy.yml`).

## Travailler en local

```bash
python3 -m venv .venv
.venv/bin/pip install -r requirements.txt
.venv/bin/mkdocs serve        # aperçu sur http://127.0.0.1:8000
.venv/bin/mkdocs build --strict
```

## Organisation

- `docs/prise-en-main/` : connexion, interface, rôles, personnalisation
- `docs/guides/` : projets, dossiers, biens, estimations, tâches, contacts, corbeille
- `docs/administration/` : utilisateurs, agences, modèles

Les pages encore incomplètes portent un encadré « Page à compléter ».
