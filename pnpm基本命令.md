以下是一些常用的 `pnpm` monorepo 命令：

### 基本命令

- **安装依赖**：

  复制

  ```
  pnpm install
  ```

- **添加依赖到指定包**：

  复制

  ```
  pnpm add <package-name> --filter <package>
  ```

- **删除依赖**：

  basic

  复制

  ```
  pnpm remove <package-name> --filter <package>
  ```

### 工作区相关

- **运行工作区根目录脚本**：

  复制

  ```
  pnpm -w run <script-name>
  ```

- **更新依赖**：

  复制

  ```
  pnpm update
  ```

- **运行指定包的脚本**：

  复制

  ```
  pnpm run <script-name> --filter <package>
  ```

### 链接和发布

- **链接包**：

  复制

  ```
  pnpm link <package> --filter <target-package>
  ```

- **发布包**：

  复制

  ```
  pnpm publish --filter <package>
  ```

### 其他

- **查看依赖树**：

  复制

  ```
  pnpm list
  ```

- **清理缓存**：

  复制

  ```
  pnpm store prune
  ```

这些命令可以帮助你高效地管理 monorepo 项目。