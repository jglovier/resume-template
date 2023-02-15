# Resume template

_A simple Jekyll + GitHub Pages powered resume template._

![img](images/screenshot.png)
After many iterations and CV styles( using JSON-resume, markdown-cv and different styles of markdown resumes) I settled on using and customizing this resume template, I already liked how it looked, so it wasn't much effort in catering it to my needs.

## What is it?

A _simple_, _minimal_, easily-modifiable and **print-friendly** website for my resume.

## Alternatives

In my searches of a good way to maintain a resume online I stumbled upon a lot of good resources and projects. I've exp

- [Elipapa's markdown CV](https://elipapa.github.io/markdown-cv/) which has a lot of themes from the community and I played with before finding this one.
  - [davewhipp's fork of markdown CV](https://github.com/davewhipp/markdown-cv)
- [Pandoc Resume](https://mszep.github.io/pandoc_resume/)
- [Hacknical](https://github.com/ecmadao/hacknical) a cool way to turn your github into a resume
- [Sproogen's resume](https://sproogen.github.io/modern-resume-theme/) which also looks like the minimal, professional CV I wanted to make.
- [Awesome Identity](https://github.com/posquit0/hugo-awesome-identity) which is a very easy to setup and configure Single Page Application powered by Hugo

## Docs

### Running locally

To test locally, run the following in your terminal:

1. Clone repo locally
1. `bundle install`
1. `bundle exec jekyll serve`
1. Open your browser to `localhost:4000`

### Running locally with Docker

To test locally with docker, run the following in your terminal after installing docker into your system:

1. `docker image build -t resume-template .`
2. `docker run --rm --name resume-template -v "$PWD":/home/app --network host resume-template`
