<p align="center">
  <a href="https://example.com/">
    <img src="https://github.com/gustavolbs/Ecoleta/blob/master/logo.png" alt="Logo">
  </a>

  <h3 align="center">E-Coleta</h3>

  <p align="center">
    Seu marketplace de coleta de resíduos<br />
    Ajudamos pessoas a encontrarem pontos de coleta de forma eficiente.
    <br>
    <a href="https://github.com/gustavolbs/Ecoleta/issues/new?template=bug.md">Reportar bug</a>
    ·
    <a href="https://github.com/gustavolbs/Ecoleta/issues/new?template=feature.md&labels=feature">Pedir nova feature</a>
  </p>
</p>

## Sumário

- [Sumário](#sumário)
- [Descrição](#descrição)
- [Status](#status)
- [O que está incluso](#o-que-está-incluso)
- [Bugs e pedidos de features](#bugs-e-pedidos-de-features)
- [Contribuindo](#contribuindo)
- [Criadores](#criadores)
- [Agradecimentos](#agradecimentos)

## Descrição

O E-Coleta é um app com o objetivo de ligar pessoas que querem descartar seus resíduos com estabelecimentos que coletam estes resíduos. Para tanto, o processo é divido em 4 partes:

1. O estabelecimento é cadastrado no E-Coleta através do site.
2. O usuário, através do aplicativo, consulta quais estabelecimentos estão cadastrados em determinada localidade de acordo com a seleção do usuário.
3. O usuário pode entrar em contato com o estabelecimento através do Whatsapp ou E-mail diretamente pelo E-Coleta.
4. O usuário descarta adequadamente seus resíduos no estabelecimento encontrado.

## Status

- Web: Disponível em https://e-coleta.netlify.app/
- Api: Disponível em https://e-coleta-api.herokuapp.com/
- Mobile: Ainda não possui build

## O que está incluso

Todo o código criado para o projeto está disposto desta forma

```text
mobile/
├── src/
│   ├── assets/
│   │   └── Imagens para projeto
│   ├── pages/
│   │   └── Página
│   │       └── index.tsx
│   ├── services/
│   │   └── api.ts
│   └── routes.tsx
└── assets/
    └── Imagens do app
server/
├── src/
│   ├── config/
│   │   └── multer.ts
│   ├── controllers/
│   │   ├── ItemsController.ts
│   │   └── PointsController.ts
│   ├── database/
│   │   ├── migrations/
│   │   │   └── Arquivos de migração
│   │   ├── seeds/
│   │   │   └── Arquivos de seed
│   │   └── connection.ts
│   ├── routes.tsx
│   └── server.ts
└── uploads/
    └── Imagens do app
web/
└── src/
    ├── assets/
    │   └── Imagens para projeto
    ├── components/
    │   └── Component
    │       ├── index.tsx
    │       └── styles.css
    ├── pages/
    │   └── Página
    │       ├── index.tsx
    │       └── styles.css
    ├── services/
    │   └── api.ts
    ├── App.tsx
    ├── index.tsx
    └── routes.tsx
```

## Bugs e pedidos de features

Encontrou um bug ou deseja uma nova feature? Por favor verifique se já não existe uma issue com tal anotação (aberta ou fechada), senão, crie-a. Você pode criar uma nova issue através deste [link](https://github.com/gustavolbs/Ecoleta/issues/new).

## Contribuindo

Para contibuir, todo o código deve estar em conformidade com o padrão desenvolvido pelos autores, mantido por [gustavolbs](https://github.com/gustavolbs).

As preferências do editor estão disponíveis no [editor config](https://github.com/Ecoleta/blob/master/.editorconfig) para facilitar o uso em editores de texto comuns. Leia mais e faça o download de plugins em <https://editorconfig.org/>.

## Criadores

**Gustavolbs**

- <https://github.com/gustavolbs>

**Rocketseat**

- <https://github.com/rocketseat>

## Agradecimentos

Obrigado a Rocketseat por proporcionar esse aprendizado dentro desta semana.
