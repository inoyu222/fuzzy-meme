# Purpose of This Repo

The repo contains the starter code for exercises used in CD12355 **Microservices at Scale using AWS and Kubernetes** course. 
#aws ecr get-login-password --region us-east-1 | docker login --username AWS --password-stdin 800040451075.dkr.ecr.us-east-1.amazonaws.com
#注意: AWS CLI の使用中にエラーが発生した場合は、最新バージョンの AWS CLI と Docker がインストールされていることを確認してください。
#以下のコマンドを使用して、Docker イメージを構築します。一から Docker ファイルを構築する方法については、「こちらをクリック 」の手順を参照してください。既にイメージが構築されている場合は、このステップをスキップします。

#docker build -t coworkingcheckin .
#構築が完了したら、このリポジトリにイメージをプッシュできるように、イメージにタグを付けます。

#docker tag coworkingcheckin:latest 800040451075.dkr.ecr.us-east-1.amazonaws.com/coworkingcheckin:latest
#以下のコマンドを実行して、新しく作成した AWS リポジトリにこのイメージをプッシュします:

#docker push 800040451075.dkr.ecr.us-east-1.amazonaws.com/coworkingcheckin:latest

