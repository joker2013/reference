# Uniq
Удаление из файла строк-дубликатов с помощью

``` bash
$ uniq
```
## Пример
``` bash
$ history | awk '{print $2}'|uniq -c |sort -n
```