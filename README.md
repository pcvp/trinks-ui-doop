# trinks-ui-doop

Publica os componentes do [trinks-ui](https://trinks-com.github.io/trinks-ui/beta/) num formato que as canvas do doop conseguem usar sem React:

- https://pcvp.github.io/trinks-ui-doop/trinks-ui.css: todo o CSS que o Chakra gera nas stories, com os `@import` das fontes
- https://pcvp.github.io/trinks-ui-doop/components.json: o HTML renderizado de cada story (`id`, `title`, `name`, `html`)

O workflow abre o Storybook beta público num Chrome headless, passa por todas as stories e copia o CSS e o HTML depois de renderizados. Ele roda a cada 30 minutos em dia útil, das 8h às 20h, e só publica de novo quando o Storybook mudou. Também dá pra disparar na mão pelo Actions.

Nada aqui vem do código do trinks-ui: é só o que o Storybook beta já mostra publicamente.
