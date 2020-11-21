# My Automatically Deployed Resume

Check it out in the 'releases' tab, or at https://github.com/ZenghaoWang/MyResume/releases/latest/download/resume.pdf

## Deployment Process

I use [this](https://github.com/posquit0/Awesome-CV) LaTeX template with a few small tweaks to the colorscheme and headers.
Every time I push the latest .tex file to master, a Github Actions workflow is triggered which compiles the source files into a pdf then creates a new release.
This is nice because it allows me to provide a static link (https://github.com/ZenghaoWang/MyResume/releases/latest/download/resume.pdf) on my website/linkedin etc which will always have the most up-to-date copy of my resume.
