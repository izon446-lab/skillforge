# skillforge

Scaffold Agent Skills: `SKILL.md` + `references/` + `examples/demo-run.md`.

## Usage
```bash
bin/skillforge new hello-skill "Say hello when the user greets you."
```
Creates:
```
hello-skill/
  SKILL.md            # frontmatter: name, description
  README.md
  references/.gitkeep
  examples/demo-run.md
```
Set `SKILLFORGE_OUT=dir` to choose the output parent (default `.`). See `examples/hello-skill/`.

## License
MIT
