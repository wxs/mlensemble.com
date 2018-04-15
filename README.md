# ML Ensemble homepage

The site is generated using the static site generator [Hugo](https://gohugo.io)

To build the site install hugo and then run `hugo` from the root of this repo. The compiled site shows up in the `public` directory
To modify speakers, edit [data/speakers.yaml](data/speakers.yaml). (Schedule,
past speakers, and sponsors are also in [data/](data/)).

The page itself is mostly defined in
[themes/mlconf/layouts/index.html](themes/mlconf/layouts/index.html), with 
whatever reason a small number of parameters, like page title and tagline, defined, instead, in
[content/_index.md](content/_index.md).


