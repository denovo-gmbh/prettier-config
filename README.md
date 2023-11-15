# 💅 @denovo/prettier-config

A [Prettier](https://prettier.io/) [configuration](https://prettier.io/docs/en/configuration.html#sharing-configurations)
for projects following the [Denovo](https://denovo.at/) coding guidelines.

## Installation

```
npm install --save-dev @denovo/prettier-config
```

## Usage

Specify `prettier` property in `package.json`:

```json
{
  "name": "another-project",
  "prettier": "@denovo/prettier-config",
  "devDependencies" : {
    "@denovo/prettier-config": "^1.0.1"
  }
}
```

Alternatively you can create a `.prettierrc.json` file with the content:

```json
"@denovo/prettier-config"
```

## How to contribute

 - Change the `.prettierrc.json` file in arrangement with the Denovo QA team.
 - Run `npm run publish` and follow the instructions.
