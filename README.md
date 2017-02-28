# my-charts

This is an example charts repository.

This is how it works:
$ helm create spark
$ helm package spark
$ mkdir docs
$ mv spark-0.1.3.tgz ./docs/
$ helm repo index docs --url https://entropysong.github.io/my-charts/
$ git add -i
$ git commit -a
$ git push origin master
$ helm repo add git-charts https://entropysong.github.io/my-charts/
