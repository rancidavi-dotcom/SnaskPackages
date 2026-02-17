# datetime

Biblioteca de data/hora (Unix epoch, durações e helpers ISO8601 simples).

## Instalação

```bash
snask install datetime
```

## Uso

```snask
import "datetime"

class main
    fun start()
        print("unix:", datetime::now_unix());
        print("iso:", datetime::iso8601_build(2026, 2, 17, 10, 30, 0));
```
