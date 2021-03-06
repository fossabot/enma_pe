# ENMA PE #

[![AppVeyor build status](https://ci.appveyor.com/api/projects/status/github/jnastarot/enma_pe?branch=master&svg=true)](https://ci.appveyor.com/project/jnastarot/enma_pe/branch/master)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fjnastarot%2Fenma_pe.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fjnastarot%2Fenma_pe?ref=badge_shield)

```
--------------------------------------------------------------------------------
Name....: enma pe
Author..: JNA
Date....: 2018
e.mail..: jnastarot@yandex.ru
--------------------------------------------------------------------------------
```
---
### supported PE\PE+ formats

| directory name | read | build | erase |
| -------------- | ------- | ------- | ------- |
| `export` | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| `import(default)` | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| `bound import` | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| `delay import` | :heavy_check_mark: | :heavy_multiplication_x: | :heavy_check_mark: |
| `resources` | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| `exceptions` | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| `security` | :heavy_multiplication_x: | :heavy_multiplication_x: | :heavy_check_mark: |
| `relocations` | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| `debug` | :heavy_check_mark: | :heavy_multiplication_x: | :heavy_check_mark: |
| `tls` | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| `load config` | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| `.NET meta data` | :heavy_check_mark: | :heavy_multiplication_x: | :heavy_multiplication_x: |

---
| helper | description |
| ------ | ----------- |
| `map parser` | parsing .map file generated by delphi XE and Visual Studio |
| `tds parser` | parsing tds-styled debug info |
| `string finder` | finding ansi and unicode strings in pe file |
---
| credits |
| ---------- |
| pe rich data [vxlab](https://vxlab.info/wasm/print.php-article=sdf.htm) |
| pe rich comp id [richprint](https://github.com/dishather/richprint/) |
| reading\building of export and resources [pe bliss kaimi](http://kaimi.io/) |
| tds parser [denisenkomik.narod.ru/main.cpp](http://denisenkomik.narod.ru/main.cpp) |



## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fjnastarot%2Fenma_pe.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fjnastarot%2Fenma_pe?ref=badge_large)