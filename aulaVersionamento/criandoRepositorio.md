# 🚀 Guia Prático: Estruturando seu Projeto React

Este guia orienta a criação da arquitetura base para o seu portfólio profissional, garantindo que a organização das pastas facilite a manutenção e o escalonamento do projeto.

---

## 📁 Arquitetura de Pastas (src)

No React, a pasta `src` é o coração da aplicação. Vamos estruturá-la seguindo os padrões de mercado:

### 1. Criando as Subpastas
Dentro de `src/`, crie as seguintes pastas:

* **`assets/`**: Para arquivos estáticos como imagens, ícones e logotipos.
* **`components/`**: Para partes reutilizáveis da interface (ex: Botões, Navbar, Cards).
* **`pages/`**: Para os componentes que representam as telas completas (ex: Home, Sobre, Contatos).
* **`styles/`**: Para arquivos de estilização global ou temas (CSS, Sass ou Styled Components).

---

## 🛠️ O uso do arquivo `.gitkeep`

**O Problema:** O Git não rastreia pastas que estão vazias. Se você criar a estrutura acima mas não colocar nenhum arquivo dentro, elas não serão enviadas para o repositório remoto (GitHub).

**A Solução:** Utilizamos um arquivo "marcador" chamado `.gitkeep`.

### Passo a passo:
1. Entre em cada pasta criada (`assets`, `components`, etc).
2. Crie um arquivo vazio com o nome exato: `.gitkeep` (não esqueça do ponto no início).
3. Salve o arquivo.

Isso "força" o Git a reconhecer a existência da pasta, mantendo sua arquitetura intacta para outros colaboradores.

---

## 🔍 Visualização da Estrutura Final

Ao finalizar, seu diretório deve seguir este modelo:

```text
nome-do-projeto/
├── public/          # Arquivos públicos e index.html
├── docs/            # Documentação e especificações do projeto
└── src/             # Código-fonte
    ├── assets/
    │   └── .gitkeep
    ├── components/
    │   └── .gitkeep
    ├── pages/
    │   └── .gitkeep
    └── styles/
        └── .gitkeep
