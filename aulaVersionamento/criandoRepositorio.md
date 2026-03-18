🚀 Atividade Prática: Organizando seu Portfólio React
Bem-vindos! Nesta etapa, vamos aprender a estruturar as pastas do nosso projeto profissional. Um repositório organizado não apenas ajuda no desenvolvimento, mas também demonstra para recrutadores que você domina boas práticas de arquitetura.

🎯 O Desafio das Pastas Vazias no Git
O Git é um sistema que rastreia arquivos, não pastas. Se você criar uma pasta vazia no seu computador e tentar subir para o GitHub, ela simplesmente não aparecerá.

Para resolver isso e garantir que todos os alunos sigam a mesma estrutura, usamos um arquivo "marcador" chamado .gitkeep.

📝 Passo a Passo da Estrutura
Siga estas instruções para criar a arquitetura base do seu portfólio:

1. Criando a Raiz do Projeto
No seu diretório principal, você deve ter a pasta src/. É nela que toda a "mágica" do React acontece.

2. Criando Subpastas e Arquivos .gitkeep
Dentro da pasta src/, vamos criar quatro subpastas essenciais. Como elas ainda não possuem código, você deve criar um arquivo chamado .gitkeep dentro de cada uma:

src/assets/: Local para imagens, ícones e fontes.

Ação: Crie a pasta e, dentro dela, um arquivo vazio chamado .gitkeep.

src/components/: Onde guardaremos nossos componentes reutilizáveis (Header, Footer, botões).

Ação: Crie a pasta e o arquivo .gitkeep.

src/pages/: Para os arquivos que representam as telas do site (Home, Projetos, Contato).

Ação: Crie a pasta e o arquivo .gitkeep.

src/styles/: Reservada para seus arquivos de CSS ou Styled Components.

Ação: Crie a pasta e o arquivo .gitkeep.

3. Pastas de Suporte
Fora da pasta src/, crie também:

public/: Para arquivos estáticos (como o index.html e o favicon).

docs/: Para documentação extra do projeto, como o planejamento ou o design feito no Figma.

🔍 Como deve ficar sua estrutura no terminal:
Plaintext
meu-portfolio-react/
├── public/
├── docs/
└── src/
    ├── assets/
    │   └── .gitkeep
    ├── components/
    │   └── .gitkeep
    ├── pages/
    │   └── .gitkeep
    └── styles/
        └── .gitkeep
💡 Dica de Ouro: Por que usar nomes em inglês?
No mercado de tecnologia, o padrão internacional é o inglês. Usar assets, components e pages em vez de "ativos", "componentes" e "paginas" prepara você para trabalhar em qualquer equipe do mundo e facilita o uso de bibliotecas que buscam essas pastas por padrão.

✅ Checklist de Entrega
[ ] Criei todas as pastas mencionadas?
[ ] Adicionei o arquivo .gitkeep onde ainda não existem arquivos de código?
[ ] Realizei o git add, git commit e git push para subir a estrutura?

[ ] Adicionei o arquivo .gitkeep onde ainda não existem arquivos de código?

[ ] Realizei o git add, git commit e git push para subir a estrutura?
