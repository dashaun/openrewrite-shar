[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

# OpenRewrite and Spring Health Assessment Report

## The cheat code

```bash
./mvnw -U org.openrewrite.maven:rewrite-maven-plugin:run \
 -Drewrite.recipeArtifactCoordinates=org.openrewrite.recipe:rewrite-spring:LATEST \
 -DactiveRecipes=org.openrewrite.java.spring.boot3.UpgradeSpringBoot_3_2
```

## Prerequisites
- [SDKMan](https://sdkman.io/install)
  > i.e. `curl -s "https://get.sdkman.io" | bash`
- [Httpie](https://httpie.io/) needs to be in the path
  > i.e. `brew install httpie`
- bc, pv, zip, unzip, gcc, zlib1g-dev
  > i.e. `sudo apt install bc, pv, zip, unzip, gcc, zlib1g-dev -y`
- [Vendir](https://carvel.dev/vendir/)
  > i.e. `brew tap carvel-dev/carvel && brew install vendir`

## Quick Start
```bash
./demo.sh
```

## Attributions
- [Demo Magic](https://github.com/paxtonhare/demo-magic) is pulled via `vendir sync`

## Related Videos

- https://www.youtube.com/live/qQAXXwkaveM?si=4KunXZaretBrPZs3
- https://www.youtube.com/live/ck4AP7kRQkc?si=lDl203vbfZysrX5e
- https://www.youtube.com/live/VWPrYcyjG8Q?si=z7Q2Rm_XOlBwCiei


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[forks-shield]: https://img.shields.io/github/forks/dashaun/openrewrite-shar.svg?style=for-the-badge
[forks-url]: https://github.com/dashaun/openrewrite-shar/forks
[stars-shield]: https://img.shields.io/github/stars/dashaun/openrewrite-shar.svg?style=for-the-badge
[stars-url]: https://github.com/dashaun/openrewrite-shar/stargazers
[issues-shield]: https://img.shields.io/github/issues/dashaun/openrewrite-shar.svg?style=for-the-badge
[issues-url]: https://github.com/dashaun/openrewrite-shar/issues
