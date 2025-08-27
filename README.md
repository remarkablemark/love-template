# Love Template

[![build](https://github.com/remarkablegames/love-template/actions/workflows/build.yml/badge.svg)](https://github.com/remarkablegames/love-template/actions/workflows/build.yml)

❤️ [LÖVE](https://love2d.org/) template to make 2D games in [Lua](https://www.lua.org/). Example from [challacade/snippets](https://github.com/challacade/snippets).

## Prerequisites

Install [LÖVE](http://love2d.org/#download):

```sh
brew install love
```

Install [Node.js](https://nodejs.org/):

```sh
brew install node
```

## Install

Clone repository:

```sh
git clone https://github.com/remarkablegames/love-template.git
cd love-template
```

Initialize and update submodules:

```sh
git submodule update --init --recursive
```

## Run

Run game:

```sh
love .
```

## Build

[Build](https://love2d.org/wiki/Game_Distribution) game:

```sh
zip -9 -r love-template.love **/*.lua assets
```

Open game:

```sh
open love-template.love
```

## Web

Build for web using [love.js](https://www.npmjs.com/package/love.js):

```sh
npx love.js love-template.love web -c -t "Love Template"
```

Run web server:

```sh
python3 -m http.server -d web
```

View game:

```sh
open http://localhost:8000/
```

## License

[MIT](LICENSE)
