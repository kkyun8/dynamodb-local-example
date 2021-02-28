# dynamodb-local-example

開発用ローカルdynamodb

参考URL<br>
https://docs.aws.amazon.com/ja_jp/amazondynamodb/latest/developerguide/DynamoDBLocal.DownloadingAndRunning.html<br>
https://dev.classmethod.jp/articles/dynamodb-nosql-workbench-datamodeling/


## nosql workbench
GUI アプリケーション<br>
https://docs.aws.amazon.com/ja_jp/amazondynamodb/latest/developerguide/workbench.settingup.html<br>
https://blog.dalt.me/301


## aws-sdk setup

```
import AWS from 'aws-sdk'

const ddb = new AWS.DynamoDB({
  endpoint: 'http://localhost:8000',
  region: 'ap-northeast-1',
  accessKeyId: 'fakeAccessKeyId',
  secretAccessKey: 'fakeSecretAccessKey'
})
```
