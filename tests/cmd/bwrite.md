## dy bwrite

```
$ dy bwrite --help
Put or Delete multiple items at one time, up to 25 requests. [API: BatchWriteItem]

https://docs.aws.amazon.com/amazondynamodb/latest/APIReference/API_BatchWriteItem.html

Usage: dy bwrite [OPTIONS] --input <INPUT>

Options:
  -i, --input <INPUT>
          Input JSON file path. This input file should be BatchWriteItem input JSON syntax. For more info: https://docs.aws.amazon.com/amazondynamodb/latest/APIReference/API_BatchWriteItem.html

  -r, --region <REGION>
          The region to use (e.g. --region us-east-1). When using DynamodB Local, use `--region local`. You can use --region option in both top-level and subcommand-level

  -p, --port <PORT>
          Specify the port number. This option has an effect only when `--region local` is used

  -t, --table <TABLE>
          Target table of the operation. You can use --table option in both top-level and subcommand-level. You can store table schema locally by executing `$ dy use`, after that you need not to specify --table on every command

  -h, --help
          Print help (see a summary with '-h')

$ dy help bwrite
Put or Delete multiple items at one time, up to 25 requests. [API: BatchWriteItem]

https://docs.aws.amazon.com/amazondynamodb/latest/APIReference/API_BatchWriteItem.html

Usage: dy bwrite [OPTIONS] --input <INPUT>

Options:
  -i, --input <INPUT>
          Input JSON file path. This input file should be BatchWriteItem input JSON syntax. For more info: https://docs.aws.amazon.com/amazondynamodb/latest/APIReference/API_BatchWriteItem.html

  -r, --region <REGION>
          The region to use (e.g. --region us-east-1). When using DynamodB Local, use `--region local`. You can use --region option in both top-level and subcommand-level

  -p, --port <PORT>
          Specify the port number. This option has an effect only when `--region local` is used

  -t, --table <TABLE>
          Target table of the operation. You can use --table option in both top-level and subcommand-level. You can store table schema locally by executing `$ dy use`, after that you need not to specify --table on every command

  -h, --help
          Print help (see a summary with '-h')

```