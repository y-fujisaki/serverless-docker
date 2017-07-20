## serverless framemework Dockerfile

* Pyrhon3.6にて、serverless frameworkでの開発環境を構築

## 使用方法
* Docker Hubに登録済
* aws configureでAWS CLIの初期設定が終わっていることを前提
* 下記コマンド実行で、Dockerコンテナ内でbash利用可能となる

```
docker run -ti --rm --name sls -v ~/.aws:/root/.aws youukkari/sls-python3 bash
```


## ライブラリ(Python)

```
astroid==1.5.3
awscli==1.11.108
beautifulsoup4==4.6.0
boto3==1.4.4
botocore==1.5.71
certifi==2017.4.17
chardet==3.0.4
colorama==0.3.7
cssselect==1.0.1
decorator==4.0.11
docutils==0.13.1
falcon==1.2.0
httpie==0.9.9
idna==2.5
isort==4.2.15
jmespath==0.9.3
lambda-uploader==1.2.0
lazy-object-proxy==1.3.1
lxml==3.8.0
mccabe==0.6.1
py==1.4.34
pyasn1==0.2.3
Pygments==2.2.0
pylint==1.7.2
python-dateutil==2.6.0
python-lambda-local==0.1.4
python-mimeparse==1.6.0
PyYAML==3.12
requests==2.18.1
retry==0.9.2
rsa==3.4.2
s3transfer==0.1.10
six==1.10.0
slackweb==1.0.5
urllib3==1.21.1
urlopen==1.0.0
virtualenv==15.1.0
wrapt==1.10.10
```
