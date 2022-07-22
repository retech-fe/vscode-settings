# vscode-settings

## 使用方式

1. 在自己的工程目录下新建`.vscode`目录，把相应的配置文件拷贝进去即可
2. 在`.gitignore`文件中配置
   ```
   .vscode/*
   !.vscode/extensions.json
   !.vscode/settings.json
   !.vscode/global.code-snippets
   ```
3. 文件说明
   - .vscode/extensions.json 扩展插件
   - .vscode/settings.json 配置项
   - vscode/global.code-snippets 代码提示 snippets

## 参考

[Anthony's VS Code Settings](https://github.com/antfu/vscode-settings)
