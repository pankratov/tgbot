# tgbot
Telegram bot minimal command line interface

Use `./tgbot -h` for help

## Examples

```shell
$ ./tgbot -t "asdfEASDFEL:asDFEASDEASD:ADAEASDFEAFvsdda" -c 1234567 -m "<b>Hello</b>, world!"

```
{"ok":true,"result":{"message_id":46,"from":{"id":543210,"is_bot":true,"first_name":"Tgbot","username":"tgbot"},"chat":{"id":1234567,"first_name":"John","last_name":"Smith","username":"jsmith","type":"private"},"date":1504909409,"text":"Hello, world","entities":[{"offset":0,"length":5,"type":"bold"}]}}


```shell
$ ./tgbot -t "asdfEASDFEL:asDFEASDEASD:ADAEASDFEAFvsdda"
```

{"ok":true,"result":[{"update_id":345,
"edited_message":{"message_id":44,"from":{"id":1234567,"is_bot":false,"first_name":"John","last_name":"Smith","username":"jsmith","language_code":"en-US"},"chat":{"id":1234567,"first_name":"John","last_name":"Smith","username":"jsmith","type":"private"},"date":1504909156,"edit_date":1504909219,"text":"Hi there"}}]}
      
```shell
$ ./tgbot -t "asdfEASDFEL:asDFEASDEASD:ADAEASDFEAFvsdda" -u 346
```
{"ok":true,"result":[]}
    
