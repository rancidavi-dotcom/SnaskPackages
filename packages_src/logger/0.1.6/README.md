# logger

Logging simples com níveis, timestamp (epoch) e escrita opcional em arquivo.

## Instalação

```bash
snask install logger
```

Dependências:

```bash
snask install colors
snask install sfs
```

## Uso

```snask
import "logger";

class main
    fun start()
        logger::set_level(0);
        logger::set_color(true);
        logger::info("app iniciou");
        logger::warn("algo estranho");
        logger::error("falhou");
```
