# vite-vue

## Prepare

### code style format

- editor config
    - create editor config file
        .editorconfig
        ```bash
        # Editor configuration, see http://editorconfig.org

        # 表示是最顶层的 EditorConfig 配置文件
        root = true

        [*] # 表示所有文件适用
        charset = utf-8 # 设置文件字符集为 utf-8
        indent_style = space # 缩进风格（tab | space）
        indent_size = 4 # 缩进大小
        end_of_line = lf # 控制换行类型(lf | cr | crlf)
        trim_trailing_whitespace = true # 去除行首的任意空白字符
        insert_final_newline = true # 始终在文件末尾插入一个新行

        [*.md] # 表示仅 md 文件适用以下规则
        max_line_length = off
        trim_trailing_whitespace = false
        ```
    - install plugin for VSCode -- EditorConfig for VS Code

- Prettier
    - use Prettier
        ```bash
        npm i prettier -D
        ```
    - create prettier config file(enable json/yml/yaml/js etc.)
        .prettierrc
        ```json
        {
            "useTabs": true,
            "tabWidth": 4,
            "printWidth": 100,
            "singleQuote": true,
            "trailingComma": "none",
            "bracketSpacing": true,
            "semi": true
        }
        ```
    - format code
        ```bash
        npx prettier --write .
        ```

- Eslint
    - install
    ```bash
    npx eslint --init
    ```
    - init
    ```bash
    npx eslint --init
    ```


## Composition Api
