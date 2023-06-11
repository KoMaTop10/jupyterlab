# DockerでPython環境を構築する

DockerでPythonの仮想環境を構築します。

`docker compose up -d`でスタートします。
終了する時は`docker compose stop`です。
エラーが出る時は`docker-compose build -d`を試してみてください

`localhost:8080`で仮想環境のjupyter labが起動できます。

ローカルのノートブックやPythonスクリプトを使用したい時はroot/workspaceに対象のノートブック,Pythonスクリプトを保存することで仮想環境で使用できます。

Pythonバージョンの変更やライブラリをインストールしたい場合はDockerfileを書き換えてください。
