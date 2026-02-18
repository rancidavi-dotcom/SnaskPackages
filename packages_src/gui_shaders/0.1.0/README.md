# GUI Shaders (Snask Library)

A `gui_shaders` é uma extensão para o ecossistema de GUI do Snask, focada exclusivamente em estilização avançada usando CSS moderno. Ela permite aplicar temas completos, efeitos de vidro (glassmorphism), glows, gradientes e animações com apenas uma linha de código.

## 🚀 Instalação

```bash
snask install gui_shaders
```

## 🎨 Funcionalidades Principais

*   **Temas**: `apply_pop_os()`, `apply_catppuccin()`, `apply_nord()`.
*   **Efeitos**: `glassmorphism(widget)`, `neon_glow(widget, color)`, `elevate(widget)`.
*   **Animações**: `pulse(widget)`, `fade_in(widget)`.
*   **Design**: `round_corners(widget, radius)`, `gradient_linear(widget, c1, c2)`.

## 🛠️ Exemplo de Uso

```snask
import "gui";
import "gui_shaders";

class main
    fun start()
        gui::init();
        gui_shaders::apply_pop_os(); // Aplica tema base
        
        let win = gui::window("Minha App", 400, 300);
        let btn = gui::button("Clique aqui");
        
        gui_shaders::elevate(btn); // Adiciona sombra e efeito de hover
        gui_shaders::neon_glow(btn, "#48b9c7"); // Adiciona brilho neon
        
        gui::show_all(win);
        gui::run();
```

## 📄 Licença
Distribuído sob a Licença MIT.
