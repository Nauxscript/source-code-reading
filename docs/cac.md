# 回到代码之源：读一读 CAC 源码顺手整个 CLI 工具

## 翻译翻译，什么是 CAC

仓库目录结构：

```
├── LICENSE
├── README.md
├── circle.yml
├── examples
│   ├── basic-usage.js
│   ├── command-examples.js
│   ├── command-options.js
│   ├── dot-nested-options.js
│   ├── help.js
│   ├── ignore-default-value.js
│   ├── negated-option.js
│   ├── sub-command.js
│   └── variadic-arguments.js
├── index-compat.js
├── jest.config.js
├── mod.js
├── mod.ts
├── mod_test.ts
├── package.json
├── rollup.config.js
├── scripts
│   └── build-deno.ts
├── src
│   ├── CAC.ts
│   ├── Command.ts
│   ├── Option.ts
│   ├── __test__
│   │   ├── __snapshots__
│   │   │   └── index.test.ts.snap
│   │   └── index.test.ts
│   ├── deno.ts
│   ├── index.ts
│   ├── node.ts
│   └── utils.ts
├── tsconfig.json
└── yarn.lock
```

### 概念与实现原理

#### Option

#### Command

#### Action

#### Negated Options

## 当我水一个仓库，我在水写什么

### 初始化

### 代码结构

### 单元测试

### 构建工具

### 持续集成

## 只欠东风

### 整点~~假~~需求

脚手架工具要解决什么问题

- 需求1
- 需求1
- 需求1
- 需求1

