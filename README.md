# jupyterlab

DockerでPythonの仮想環境を構築します。

`docker compose up -d`でスタートします。
終了する時は`docker compose stop`です。

`localhost:8080`でjupyter labが起動できます。

ローカルのノートブックやPythonスクリプトを使用したい時はroot/workspaceに対象のノートブック,Pythonスクリプトを保存することで仮想環境で使用できます。

ライブラリをインストールしたい場合はDockerfileを書き換えてください。
