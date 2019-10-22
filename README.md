# 技术备忘录

## 使用 `ndk-build` 生成 *compile_commands.json* 文件

```sh
ndk-build compile_commands.json        # 仅生成文件
ndk-build GEN_COMPILE_COMMANDS_DB=true # 生成文件同时构建项目
```

该文件可以被一些提供自动补全功能的程序使用, 例如 Vim 插件 coc-nvim.
