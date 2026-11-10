# Meus Apps

Página inicial que reúne os aplicativos web publicados em
[github.com/alessandrociapina-cpu](https://github.com/alessandrociapina-cpu).

Publicada pelo GitHub Pages em **https://alessandrociapina-cpu.github.io/**.

## Adicionar um app

Edite a lista `APPS` no `index.html` e inclua um objeto:

```js
{
  repo: 'nome-do-repositorio',
  nome: 'Nome exibido',
  icone: '🛠️',
  cat: 'campo', // sinistros | campo | documentos | estudo
  desc: 'Uma frase sobre o que o app faz.',
},
```

Sem o campo `url`, o botão **Abrir** aponta para `https://alessandrociapina-cpu.github.io/<repo>/`.
Para um app hospedado em outro lugar (ex.: Vercel), informe `url: 'https://...'`.

A página é um único arquivo HTML, sem dependências nem etapa de build.
