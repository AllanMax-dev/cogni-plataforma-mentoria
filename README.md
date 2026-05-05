# Cogni

![Logo Cogni](assets/img/logo_com_fundo.png)

## Sobre

A **Cogni** é um protótipo de plataforma web para mentorias online.

A ideia do projeto é permitir que alunos encontrem mentores, visualizem perfis, escolham horários disponíveis, simulem o pagamento e acompanhem suas mentorias em uma agenda.

O projeto também possui uma área para mentores, onde é possível visualizar o perfil, editar informações e gerenciar horários disponíveis.

## Funcionalidades

- Login e cadastro de usuários
- Separação entre perfil de aluno e mentor
- Dashboard para aluno
- Dashboard para mentor
- Busca de mentores
- Perfil detalhado do mentor
- Agendamento de mentoria
- Pagamento simulado
- Calendário de mentorias
- Página de detalhes da sessão
- Gerenciamento de agenda do mentor
- Dados simulados com `localStorage`

## Tecnologias

- HTML
- CSS
- JavaScript
- LocalStorage
- Font Awesome
- Google Fonts

## Como executar

Clone o repositório:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
````

Acesse a pasta:

```bash
cd seu-repositorio
```

Abra o arquivo `index.html` no navegador.

Também é possível executar com a extensão **Live Server** no VS Code:

1. Abra o projeto no VS Code
2. Clique com o botão direito em `index.html`
3. Selecione **Open with Live Server**

## Contas de teste

### Aluno

```txt
E-mail: aluno@cogni.com
Senha: 123456
```

### Mentor

```txt
E-mail: mentor@cogni.com
Senha: 123456
```

## Estrutura básica

```txt
cogni/
├── index.html
├── assets/
│   └── img/
│       └── logo.png
├── styles/
│   └── style.css
├── scripts/
│   ├── auth.js
│   └── script.js
└── pages/
    ├── aluno/
    └── mentor/
```

## Observação

Este projeto ainda não possui backend.
A autenticação, os usuários, os mentores, os horários e as mentorias são simulados no navegador usando `localStorage`.

## Autor

Desenvolvido por **Allan Max**.

* [LinkedIn](https://www.linkedin.com/in/allan-max-jrl)
* [GitHub](https://github.com/AllanMax-dev)
