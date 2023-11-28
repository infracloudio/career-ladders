# InfraCloud Career Ladders

Site: <https://career-ladders.infracloud.io/docs/>

You may agree that naming is everything in the software industry - from variable names to class names, but how about extending the idea to the names of roles? Let’s say you are a “Senior Software Engineer” - great but what does that even mean? Does the name & definition translate across companies? Does everyone think exactly the same thing when they say “Senior Software Engineer”? The answer to almost all these questions is in the negative.

In such cases, unfortunately, only naming does not address the problem completely! That’s where the career laddering framework comes into the picture. It charts out how each role/position translates to actual responsibilities, skills, traits, etc. This helps to have more clarity about your current role, what all is expected of you at each level, how to move to the next level, and so on.

Read [the announcement post](https://infracloud.io/blogs/infracloud-career-laddering-framework/) to know how we reached a point where we came up with our own career laddering framework, how we built it, and what we learned along the way.

This repository hosts the source of the InfraCloud Career Ladders website.

## How to build the site
This website uses the [Hugo](https://gohugo.io/) static site generator and the [Hextra theme](https://imfing.github.io/hextra/docs/).

Website content is under the `content/docs` directory. The website home page redirects to `/docs`.

```bash
# serve locally at localhost:1313
$ hugo server

# build the website pages
$ hugo build
```

## Credits and License

A lot of inspiration for this work came from:
* Sarah Dresner’s framework <https://career-ladders.dev/engineering>
* Some good inputs from [Medium’s Growth Rubrik framework](https://docs.google.com/spreadsheets/d/1EO-Dbsayn8Nz9Ii3MKcwRbt-EIJ2MjQdpoyhh0tBdZk/edit#gid=2049640133)
* [Creating a career ladder for engineers - Marco Rogers](https://www.youtube.com/watch?v=jA1Q94d2z10)

This repository is licensed under [Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/). See [LICENSE](./LICENSE) for the full license text.

The website favicon is Ladder by Gregor Cresnar from <a href="https://thenounproject.com/browse/icons/term/ladder/" target="_blank" title="Ladder Icons">Noun Project</a> (CC BY 3.0)
