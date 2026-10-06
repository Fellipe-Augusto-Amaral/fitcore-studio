# fitcore-studio

Site desenvolvido para o estudo de caso do **Studio FitCore**, da disciplina **Design Profissional**.

O projeto apresenta uma solução digital para ajudar o estúdio a organizar melhor os treinos e melhorar o acompanhamento dos alunos.

**Site:** https://Fellipe-Augusto-Amaral.github.io/fitcore-studio/

## Sobre o projeto

O Studio FitCore trabalha com treinamento personalizado, atendendo alunos de reabilitação, emagrecimento e treino funcional.

O problema apresentado no estudo de caso é que o estúdio cresceu e o uso de fichas de treino em papel começou a dificultar o trabalho. Atualmente são 80 alunos e 3 personal trainers.

Com isso, alguns problemas começaram a aparecer:

* alunos perdem as fichas de treino;
* alguns esquecem as cargas e a forma correta de fazer os exercícios;
* os professores gastam bastante tempo preparando fichas;
* alguns treinos precisam ser enviados pelo WhatsApp;
* fica mais difícil acompanhar a evolução dos alunos;
* o estúdio tem dificuldade para atender novos alunos.

## Solução

Para o projeto, escolhi desenvolver um **site responsivo com uma demonstração de um sistema de acompanhamento de treinos**.

A ideia é mostrar como o FitCore poderia usar uma ferramenta própria para facilitar o acompanhamento dos alunos, sem deixar de lado o atendimento personalizado.

O projeto possui diferentes visões:

* **Aluno:** pode visualizar o treino, metas e informações sobre os exercícios;
* **Personal:** consegue visualizar os alunos e acompanhar algumas informações;
* **Sócios:** possui uma visão geral com dados de retenção.

Também foi incluída uma mensagem do personal dentro da ficha de treino para manter a ideia de acompanhamento mais próximo.

## Telas

A página funciona como um protótipo do sistema.

Os prints das principais telas ficam dentro da pasta `docs/`:

| Tela              | Arquivo                  |
| ----------------- | ------------------------ |
| Página inicial    | `docs/tela-inicio.png`   |
| Visão do aluno    | `docs/tela-aluno.png`    |
| Visão do personal | `docs/tela-personal.png` |
| Visão dos sócios  | `docs/tela-socios.png`   |

Os dados apresentados no projeto são fictícios e foram utilizados somente para demonstração.

## Tecnologias utilizadas

* HTML5
* CSS3
* JavaScript
* Git e GitHub
* GitHub Pages

O projeto é um site estático e não utiliza banco de dados ou backend.

## Estrutura do projeto

```text
fitcore-studio/
├── index.html
├── img/
├── docs/
├── .gitignore
├── LICENSE
└── README.md
```

As imagens utilizadas no site ficam na pasta `img/` e os prints das telas ficam na pasta `docs/`.

## Como executar

Para baixar o projeto:

```bash
git clone https://github.com/Fellipe-Augusto-Amaral/fitcore-studio.git
```

Depois entre na pasta:

```bash
cd fitcore-studio
```

Também é possível abrir o arquivo `index.html` diretamente no navegador.

Outra opção é iniciar um servidor local:

```bash
python3 -m http.server 8000
```

Depois, basta acessar `http://localhost:8000` no navegador.

## Observações

O formulário presente no site é apenas demonstrativo e não envia dados para um servidor.

Não foram utilizadas senhas, tokens ou chaves de API no projeto.

## Licença

Este projeto está disponível sob a licença MIT. Consulte o arquivo `LICENSE` para mais informações.
