# gui_app

App helpers em cima do gui (window, state simples, callbacks).

## Instalação

```bash
snask install gui_app
```

## Uso

```snask
import "gui";
import "gui_app";

class main
    fun start()
        if gui_app::init() == false
            print("sem display");
            return nil;
        let win = gui_app::window("Demo", 320, 180, true);
        gui_app::show(win);
        gui_app::run();
```
