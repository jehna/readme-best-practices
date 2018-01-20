# Readme Best Practices
> A place to copy-paste your README.md from

One of the most crucial things in your open source project is the `README.md`
file. This repository has a ready-to-copy-paste template you can use for all
your projects.

## Getting started

Copy the `README-default.md` file for yourself and start editing! At the root of
your project, run:

```shell
curl https://raw.githubusercontent.com/jehna/readme-best-practices/master/README-default.md > README.md
```

The code above fetches the `README-default.md` file from this repository and
renames it to `README.md`.

## Fill with your own text nn

The default template has some guiding text to get you started. However you'll
need to edit the file with your own text to use it with your project.

```shell
atom README.md
```

If you're using [Atom](https://atom.io/) code editor, the code above opens the
file for editing. If necessary, substitute with your preferred markdown editor.

### Add to git and push

After you've filled your `README.md` file with your own project's text, you
should push it to your GitHub project:

```shell
git add README.md
git commit -m "Added: README"
git push
```

This adds the `README.md` file to your git repository, creates a commit for it
and pushes it to GitHub (or other preferred remote repository).

## Features

This project makes it easy to:
* Bootstrap your open source project properly
* Make sure everyone gets what you're trying to archive with your project
* Follow simple instructions for a perfect `README.md`

## Contributing

As I use this for my own projects, I know this might not be the perfect approach
for all the projects out there. If you have any ideas, just
[open an issue][issues] and tell me what you think.

If you'd like to contribute, please fork the repository and make changes as
you'd like. Pull requests are warmly welcome.

If your vision of a perfect `README.md` differs greatly from mine, it might be
because your projects are for vastly different. In this case, you can create a
new file `README-yourplatform.md` and create the perfect boilerplate for that.

E.g. if you have a perfect `README.md` for a Grunt project, just name it as
`README-grunt.md`.

## Licensing

This project is licensed under Unlicense license. This license does not require
you to take the license with you to your project.

[issues]:https://github.com/jehna/readme-best-practices/issues/new
