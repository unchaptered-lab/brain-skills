# brain-skills Agent Entrypoint

Governed by `brain`.

- Read `../brain/AGENTS.md`.
  using: `sed -n '1,120p' ../brain/AGENTS.md`

- Read `../brain/rules/brain-skills/AGENTS.md`.
  using: `sed -n '1,120p' ../brain/rules/brain-skills/AGENTS.md`

Bootstrap:

```bash
../brain/scripts/governance/bootstrap.sh
```

Check:

```bash
../brain/scripts/governance/check.sh --current-repo
```

