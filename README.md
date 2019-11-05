Build your paper with GitHub actions
====================================

This will use GitHub Actions to build your LaTeX manuscript and push the compiled PDF back to GitHub. It assumes that your manuscript is `paper/ms.tex`, but this can be changed by editing `MANUSCRIPT_PATH` in `action.yml`.

This is nothing new. Dan Foreman-Mackey (@exoplaneteer) made it work with Travis CI, but now since GitHub Actions are _new on the block_, I thought I'd try them out. They're pretty sweet!

Next step,... `latexdiff`...
