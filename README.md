独習Scalaz勉強リポジトリ
===

# 環境構築
1. Dockerイメージを展開 `kzmake/jupyter-scala` : https://hub.docker.com/r/kzmake/jupyter-scala/
    ```
    $ docker run -it -p 8888:8888 -v $(pwd):/home/jovyan/work kzmake/jupyter-scala start-notebook.sh --NotebookApp.token=''
    ```

    ```
    $ docker-compose up -d
    ```
1. Jupyter Notebook(with scala v2.12.2)で独習scalaz開始
    * http://localhost:8888/

# 目的
* 独習Scalazをやる
    - http://eed3si9n.com/learning-scalaz
    
# ルール
* 21日で学べる構成になっているので、毎日1日分やる
* 途切れたらお寿司を奢る

# watching
* https://github.com/teitaraku/learning-scalaz
