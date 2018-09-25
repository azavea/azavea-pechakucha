# Azavea PechaKucha

[PechaKucha](https://www.pechakucha.org/) is a popular presentation format
where a speaker does a short presentation to image slides that auto advance
every few seconds. This keeps talks short, to the point, and interesting!

This tool is a configurable presentation viewer for such a presentation. It
uses [RevealJS](https://revealjs.com/) to load images and auto-advance the
slides. The images are loaded from a given GitHub user's repository, which is
expected to have JPEG images in the root named in order, like `1.jpg`, `2.jpg`,
`3.jpg` and so on. For an example repository, see
[rajadain/pechakucha-avengers](https://github.com/rajadain/pechakucha-avengers).

To use the tool, make a repo like the above with your slides. Then, go to [the
tool](https://azavea.github.io/azavea-pechakucha/) and fill in your username,
repository, the number of slides, delay per slide, preferred background color,
and click "Present". The presentation will start immediately!
