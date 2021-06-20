![](/readme/logo.png)

O Inmana é um gerenciador de estoques que te avisa sempre que algum de seus produtos estiver chegando na data de vencimento.

- Podem ser cadastrados restaurantes e suprimentos
- Deve ser possível visualizar informações de um suprimento
- Deve ser gerada uma relação de itens à vencer toda semana para cada um dos restaurantes
- A relação de intens deve ser enviada para o e-mail do Restaurante

Esse projeto foi proposto durante a semana Next Level Week #5 da [Rocketseat](https://rocketseat.com.br). Sobre a mentoria de [Rafael Camarda
](https://github.com/RafaelCamarda)

⚙ **Tecnologias Utilizadas**

- [Elixir](https://elixir-lang.org/)
- [Phoenix](https://phoenixframework.org/)

Para iniciar seu Phoenix server:

- Instale o phoenix com `mix archive.install hex phx_new 1.5.8`
- Instale as dependências com `mix deps.get`
- Crie e migrate seu banco de dados com `mix ecto.setup`
- Inicie o Phoenix endpoint com `mix phx.server`
- Caso precise, alterar as configurações do banco de dados pelo arquivo `dev.exs` e `config/test.exs`

Agora você pode acessar [`localhost:4000`](http://localhost:4000) pelo seu navegador.
