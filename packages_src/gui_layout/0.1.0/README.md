# gui_layout

Helpers de layout em cima do gui (containers, build helpers).

## Instalação

```bash
snask install gui_layout
```

## Uso

```snask
import "gui_layout";

class main
    fun start()
        // exemplo: cria um vbox dentro de outro container
        // (no app real você usaria gui::window + gui::set_child etc.)
        print(gui_layout::version());
```
