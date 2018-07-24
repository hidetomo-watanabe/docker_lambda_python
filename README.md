# docker_lambda_python
### command
- cp requirements.txt.org requirements.txt
- <ファイル編集>
- cp lambda_function.py.org lambda_function.py
- <ファイル編集>
- docker build -t hoge .
- docker run -d --name hoge hoge
- docker cp hoge:/var/task/deploy_package.zip .
