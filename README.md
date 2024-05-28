## To create a bun react app follow the instructions

```bash
$ bun create vite <your-project-name>
cd <project-name>
```

### Build production bundle for react app
### By default bun does not ship with react-scripts so you need to install it first.

```bash
bun a react-scripts -d
```

### Here we install it as a dev dependency.
### Then run the following command to build the production bundle

```bash
bun react-scripts build
```

### When you run the command above it will build the production bundle and it will be stored in the build directory.

### Adding scripts to your package.json
### We can add the following scripts to our package.json file

```bash
{
  "scripts": {


    "start": "bun dev",
    "build": "react-scripts build"


  }
}
```

### Add this two line inside "scripts" 

```bash
    "start": "bun dev",
    "build": "react-scripts build"
```

### Now we can run the following command to start the app

```bash
bun start
```

### And we can run the following command to build the production bundle

```bash
bun run build
```

---

**Credits to: https://github.com/AshirbadGudu/bun-react-app**

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
