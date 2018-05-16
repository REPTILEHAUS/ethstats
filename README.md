# ethstats

Go implementation of an ethstats collection server.


## Notes

First message looks like this:

```json
{
  "emit": [
    "hello",
    {
      "id": "foo",
      "info": {
        "name": "foo",
        "node": "Geth/v1.8.3-unstable/linux-amd64/go1.10",
        "port": 30303,
        "net": "1",
        "protocol": "les/2",
        "api": "No",
        "os": "linux",
        "os_v": "amd64",
        "client": "0.1.1",
        "canUpdateHistory": true
      },
      "secret": ""
    }
  ]
}
```


## License

MIT.
