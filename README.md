# plan2react

This is a reboot of Plan2Adapt using React, React-router, and Redux.

## Usage

Use `npm run` to get a list of all commands.

Basics are:

- `npm start`: Will start up the dev webserver
- `npm test`: Run unit tests
- `npm run dist`: Create the packed version

## Developing

Development has been kickstarted with the [react-webpack-redux](https://github.com/stylesuxx/generator-react-webpack-redux) generator.

### Generating new reducers

```bash
yo react-webpack-redux:reducer my/namespaced/reducers/name
yo react-webpack-redux:reducer items
```

### Generating new actions

```bash
yo react-webpack-redux:action my/namespaced/actions/name
yo react-webpack-redux:action items/addItem
```

### Generating new components

```bash
yo react-webpack-redux:component my/namespaced/components/name
```

## Generating new containers

```bash
yo react-webpack-redux:container my/namespaced/container/Name
```
