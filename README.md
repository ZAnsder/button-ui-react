# button-ui-react
基于React的Button组件，包含了Hooks、单元测试、文档生成、NPM发布以及Travis CI等全流程学习DEMO

## 📦 如何安装

```bash
npm install button-ui-react
```

```bash
yarn add button-ui-react
```

## 🔨 如何使用

```ts
import { Button } from 'button-ui-react';

const App = () => (
    <Button>默认按钮</Button>
);
```

添加组件样式:

```ts
import 'button-ui-react/dist/index.css';
```

## 📃 文件结构

```
bui-eact/
  README.md
  node_modules/
  tsconfig.json
  package.json
  .gitignore
  src/
    components/
      Button/
        styles/
          ...
        button.tsx
        button.test.tsx
        button.scss
      Alert/
        ...
    scss/
      _mixin.scss
      ...
      index.scss
    ...
```