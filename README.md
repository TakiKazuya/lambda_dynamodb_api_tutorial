# AWS Lambda + DynamoDB チュートリアル

## デプロイ手順
1. `sam build`
2. `sam deploy --guided`
   * すべてEnterでOK
   * 下記のエラーが発生した場合、awsコンソールのCloudFormationを開き、東京リージョンの`aws-sam-cli-managed-default`スタックを削除する
   ```
   　　Stack aws-sam-cli-managed-default is missing Tags and/or Outputs information and therefore not in a healthy state Failing as the stack was likely not created by the AWS SAM CLI
   ```

## 元記事
* [Lambda + DynamoDBチュートリアル](https://docs.aws.amazon.com/ja_jp/apigateway/latest/developerguide/http-api-dynamo-db.html#http-api-dynamo-db-invoke-api)
* [AWS SAM デプロイチュートリアル](https://docs.aws.amazon.com/ja_jp/serverless-application-model/latest/developerguide/serverless-getting-started-hello-world.html)