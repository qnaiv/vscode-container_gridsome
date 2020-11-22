# vscode remote container(gridsome)

## 前提条件

-   Docker と Docker Compose がインストールされていること。
-   VSCode に[Remote \- Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)がインストールされていること

> [Developing inside a Container](https://code.visualstudio.com/docs/remote/containers)の Installation までを参照。

## 使い方

1. リポジトリを clone して VSCode で開く。
2. "ReOpen in Container"を押す。
3. gridsome プロジェクトを作成する

    ```sh
    gridsome create [プロジェクト名]
    # テンプレート(https://gridsome.org/starters/)を使う場合
    # 例: gridsome create my-gridsome-site https://github.com/gridsome/gridsome-starter-blog.git
    ```

4. gridsome プロジェクトを起動する

    ```sh
      cd [プロジェクト名]
      npm run devlop
    ```

## サンプルプロジェクト

`gridsome-sample`ディレクトリにサンプルの gridsome プロジェクトが格納されている。

-   typescript 導入済み
-   ESLint + Prettier 導入済み

### 起動方法

```sh
cd gridsome-sample/
npm run develop
```

## VSCode Extensions

-   [Bracket Lens](https://marketplace.visualstudio.com/items?itemName=wraith13.bracket-lens)
-   [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
-   [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
-   [TabNine](https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode)
-   [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)
-   [Visual Studio IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)
-   [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
-   [GraphQL for VSCODE](https://marketplace.visualstudio.com/items?itemName=kumar-harsh.graphql-for-vscode)
