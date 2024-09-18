
This repro runs on latest Astro@5.0

create an .env file add libsql credentials before running the following commands.

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `bun install`             | Installs dependencies                            |
| `bun astro db push`             | Pushes schema       |
| `bun astro dev`           | Starts local dev server at `localhost:4321`          |
| `bun astro build`         | Build your production site to `./dist/`     |
| `bun astro preview ...`       | Preview your build locally, before deploying |
| `bun astro sync` | Get help using the Astro CLI                     |


