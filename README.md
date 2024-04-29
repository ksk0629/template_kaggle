# Template Kaggle
This is for kaggle.

# Docker command
- Run a container: `docker run -itd -p 8888:8080 --mount type=bind,source=/Users/ksk/dev/github/kaggle,target=/home/github --name kaggle gcr.io/kaggle-images/python:ci-pretest /bin/bash`.
- Go into the container: `docker exec -it laravel_app bash`.

# Troubleshootings
- [How to Use/Create Utility Scripts](https://www.kaggle.com/code/acchiko/how-to-use-create-utility-scripts)
- [How to add my own dataset to use another session](https://www.kaggle.com/docs/datasets)

# References
## Repository
- [【Kaggleのフォルダ構成や管理方法】タイタニック用のGitHubリポジトリを公開しました](https://upura.hatenablog.com/entry/2018/12/28/225234)
- [Kaggleで使えるFeather形式を利用した特徴量管理法](https://amalog.hateblo.jp/entry/kaggle-feature-management)

## Environment
- [Kaggle notebookとGoogle Colabのデータ連携](https://qiita.com/nekot0/items/80d903a32ee101b165b6)
- [Colab で Kaggle (N番煎じ)](https://zenn.dev/mst8823/articles/da505dcf45474f)
- [Google ColabでKaggleのデータを使用する方法（APIを利用）](https://koruriblog.com/kaggle-api/)
- [Google ColaboratoryでKaggle環境を整える時の知っておくと良いことまとめ](https://qiita.com/shigeb/items/50763ef27fb927c085c0)
- [Kaggle環境の構築方法(GPUなし)](https://qiita.com/kyotoman/items/ebd1845ae19e17dc8808)
