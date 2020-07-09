# shippable_test
EC2
ストレージスナップショット：https://docs.aws.amazon.com/ja_jp/AWSEC2/latest/UserGuide/ebs-creating-snapshot.html#ebs-create-snapshot
停止・起動：https://docs.aws.amazon.com/ja_jp/AWSEC2/latest/UserGuide/Stop_Start.html#starting-stopping-instances

S3
停止：https://docs.aws.amazon.com/ja_jp/AmazonS3/latest/user-guide/delete-objects.html
バージョニングを有効にしないと復元はできない：
https://docs.aws.amazon.com/ja_jp/AmazonS3/latest/user-guide/enable-versioning.html
復元：https://docs.aws.amazon.com/ja_jp/AmazonS3/latest/user-guide/undelete-objects.html

ElasticBeanstalk
停止：https://docs.aws.amazon.com/ja_jp/elasticbeanstalk/latest/dg/using-features.terminating.html#using-features.terminating.CON
復元：https://docs.aws.amazon.com/ja_jp/elasticbeanstalk/latest/dg/environment-management-rebuild.html#environment-management-rebuild-terminated

API Gateway
見つからなかった

Elasticache
停止：https://docs.aws.amazon.com/ja_jp/AmazonElastiCache/latest/mem-ug/Clusters.Delete.html#Clusters.Delete.CON
復元：Redisのみ・・・

ELB
終了：https://docs.aws.amazon.com/ja_jp/elasticloadbalancing/latest/network/load-balancer-delete.html


Lambda
終了：アクション　＞　関数の削除
復元：https://qiita.com/afukuma/items/a38e5255c142eff4ce63
もしくは普通に関数のエクスポート：https://hatarakitakunai-hito.net/post-354/

DynamoDB
終了：テーブル　＞　対象テーブルのチェックを入れる　＞　テーブルの削除
復元：https://docs.aws.amazon.com/ja_jp/amazondynamodb/latest/developerguide/backuprestore_HowItWorks.html

Kinesis datastream
終了：https://docs.aws.amazon.com/ja_jp/streams/latest/dev/managing-streams-console.html
復元：見つからなかった

AmazonECR
リポジトリの削除：https://docs.aws.amazon.com/ja_jp/AmazonECR/latest/userguide/repository-delete.html
イメージの削除：https://docs.aws.amazon.com/ja_jp/AmazonECR/latest/userguide/delete_image.html

CloudSearch
ドメインの削除：https://docs.aws.amazon.com/ja_jp/cloudsearch/latest/developerguide/deleting-domains.html


AWSQueueService
停止・有効化：https://docs.aws.amazon.com/ja_jp/mediaconvert/latest/ug/optional-pause-the-queue.html

awskms
有効化・無効化：https://docs.aws.amazon.com/ja_jp/kms/latest/developerguide/enabling-keys.html
