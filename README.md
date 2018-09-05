# greenplum-_CentOS7

※S3 への接続に使用するconfigファイルについて
下記のコマンドでS3へ接続するためのconfigファイルを作成し、AccessID および SecretKey を設定する。
gpcheckcloud -t > ./mytest_s3.config

作成したconfigファイルはmasterおよび全てのsegmentの下記ディレクトリに配置する。
"指定したディレクトリ"/gpseg_prefixN/s3/s3.conf
