# Personal Website

This repository is the code for my Github Pages website.  
To make changes [install Hugo](https://gohugo.io/) and have a look to
the repository of the [Hugo Coder theme](https://github.com/luizdepra/hugo-coder).

## Notes

### Add new pages

- Switch to the `dev` branch
- Launch `hugo new path/to/the/page.md`
- Set `draft : false`
- Commit

### Add new button

To add a new button modify the **config.yml** and add a new button with the `menu.main`
command.  

### Add new icons (social links)

To add a new icon, modify the **config.yml** and add a new icon with the `params.social`
command.  
New icons can be found in [Font Awesome](https://fontawesome.com).

### Render the site content

- Launch `cd public`
- Switch to the `master` branch
- Lauch `hugo`
- Commit

### Commit to dev branch

- Render the site on public folder with `hugo`
- Launch `git add -- . ':!public/'`
- Launch `git commit -m "Commit message"`
- Launch `git push origin dev`
