# Getting Started

To start a Lyra project, we suggest you use @enwrap/lyra-cli. Use the method below to start a lyra project.

```bash
npm i -g @enwrap/lyra-cli
lyra init <projectName>
```

Tips: you can also use yarn

```bash
yarn global add @enwrap/lyra-cli
lyra init <projectName>
```

This will create a project named <projectName>. Suppose the project is named example.

```bash
cd example
npm install
```

or yarn 

```bash
yarn install
```

The file structure would look like this

```
|--- .lyra
||--- config.yml //yaml format config file
|--- app //if you enabled the babel compile, the compiled file will store here
|--- src //sourcecode directory
||--- controller
||--- logic
||--- model
|||--- index.js
|--- view
||--- index_index.html
```

