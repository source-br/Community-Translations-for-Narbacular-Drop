# How to Navigate the Repository

### Project Structure

The project is organized at the root with a folder for each language, such as `PT-BR`. Inside, you will find everything related to the Portuguese translation.

The structure inside the `EN` folder consists of:

`Original` folder where the files extracted from `File.ore` are stored, keeping only what can be translated.

`Recriation` folder where the recreated contents in `.psd` are stored.

The repository is organized as follows:
```
Repo/
├── EN/
│   ├── Original/
│   │   └── levels/
│   │   └── video/
│   └── Recriation/
│       └── levels/
│       └── video/
│           └── psd/
```

The structure inside the language folders, such as PT-BR, consists of:

`Compilation (in the language folder, in this case Compilação)` folder where the ready-to-use mod is stored to be placed in the game.

`Translated (in the language folder, in this case Traduzido)` folder where the translation contents are stored, such as the `.psd` texture files.

The repository is organized as follows for `PT-BR`:
```
PT-BR/
├── Compilação/
├── Traduzido/
│   ├── levels/
│   └── video
│       └── psd/
```


<hr />

<p align="center"><strong>Documentation</strong></p>

<p align="center">
  <a href="Introduction.md">← Introduction</a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="Programs.md">Programs Used →</a>
</p>