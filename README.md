# Dockerized @ ViteJS + Tailwind + Handlebars

Scaffold a new project using dokerized boilerplate of ViteJS, TailwindCSS and Handlebars.

**Note:** This is dockerized version of [ViteJS + Tailwind + Handlebars Bolerplate](https://github.com/dendrofen/vitejs-tailwind-handlebars)

## Packages

- [ViteJS](https://github.com/vitejs/vite)
- [TailwindCSS](https://github.com/tailwindlabs/tailwindcss)
- [HandlebarsJS](https://github.com/alexlafroscia/vite-plugin-handlebars)

## Demo

Project contains 2 web pages demo, implementing all essentials code structures of used packages.
Run or build project to see, and modify. You can empty src folder in case to start project from scratch.

## Run Locally

#### Clone the project

```bash
  git clone https://github.com/dendrofen/docker-vitejs-tailwind-handlebars
```

#### Go to the project directory

```bash
  cd docker-vitejs-tailwind-handlebars
```

#### Run docker

```bash
  docker compose up
```

## Build Locally

To build this project run

```bash
  docker compose -f docker-compose.build.yml up
```

## Preview Build Locally

To preview built project

```bash
  docker compose -f docker-compose.preview.yml up
```
