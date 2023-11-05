# Clickdapp POC

The clickdapp is a repository that implements Plasmic App Hosting and Near VM to provides powerful tools to make dapps with Plasmic Studio.

## Installation
ClickDapp is powered by [**Plasmic**](https://github.com/plasmicapp/plasmic).

If you have any problems configuring your enviroment, or hosting this app, remember to read the [Plasmic App Hosting Documentation](https://docs.plasmic.app/learn/app-hosting/).

-----------------

#### Steps
1) Clone the repository:
```bash
$ gh repo clone 1Mateus/ethlisbon_poc
$ cd ethlisbon_poc
```

2) Check all packages and copy the .env.example file and edit it with your environment config:
```bash
$ cp .env.example .env
```

3) Install frontend dependencies via PNPM
```bash
$ pnpm install
```

4) Start App Hosting
```bash
$ pnpm dev
```
