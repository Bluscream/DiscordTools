# Tools

## [Discord Message Splitter](https://bluscream.github.io/DiscordTools/message/split.html)

| Parameter | Type   | Required | Description                                                                                          | Example                |
|-----------|--------|----------|------------------------------------------------------------------------------------------------------|------------------------|
| prefix    | string | No       | Each chunk will have this string prepended and the chunk length is reduced to `2000 - prefix.length` | `?prefix=!ban%20`      |
| input     | string | No       | Prefills inpit field                                                                                 | `?input=<list of ids>` |
| suffix    | string | No       | Each chunk will have this string appended and the chunk length is reduced to `2000 - suffix.length`  | `?suffix=%201day`      |
