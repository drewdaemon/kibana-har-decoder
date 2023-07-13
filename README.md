## Kibana HAR Decoder

By default, Kibana compresses batch search requests between the client and the server. This can make it difficult to troubleshoot issues using HAR files provided by customers.

The customer can disable compression using the `bfetch:disableCompression` advanced setting, but this tool just makes it one step easier.
