# 🐾 Patinhas Felizes – Site de Petshop (Fase 1)

Projeto da disciplina **Fundamentos de Sistemas Web**.
Site estático desenvolvido apenas com **HTML5**, sem CSS, Bootstrap ou JavaScript (que serão trabalhados na Fase 2).

## Funcionalidades

| Página | Arquivo | O que faz |
|---|---|---|
| Início | `index.html` | Apresenta o petshop, as categorias e a tele-busca, com links para as demais páginas. |
| Produtos | `produtos.html` | Mostra 3 categorias (Alimentação, Higiene e Beleza, Brinquedos e Acessórios), com 2 produtos cada: foto, descrição e valor. |
| Serviços | `servicos.html` | Tabela com descrição, valor e indicação de tele-busca (Sim/Não) de cada serviço. |
| Contato | `contato.html` | Endereço, telefone, e-mail e horário de funcionamento. |

Todas as páginas têm **cabeçalho** (nome, informações e menu de navegação) e **rodapé** (autoria, contato e links de navegação).

## Estrutura de pastas

```
petshop/
├── index.html
├── produtos.html
├── servicos.html
├── contato.html
├── README.md
├── img/          # imagens dos produtos (SVG)
└── css/
    └── estilo.css  # tema branco, azul e rosa (usado na Fase 2)
```

## Como visualizar

Baixe os arquivos e abra o `index.html` em qualquer navegador.

## Como publicar no GitHub Pages

1. Crie um repositório no GitHub (ex.: `petshop`) e envie todos os arquivos desta pasta.
2. No repositório, abra **Settings → Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**, selecione a branch `main` e a pasta `/ (root)` e clique em **Save**.
4. Aguarde alguns minutos. O site ficará em `https://github.com/romaszw/petshop-patinhas-felizes.git`.
```html
<!-- <link rel="stylesheet" href="css/estilo.css"> -->
```

## Personalize antes de entregar

- Troque **Nome do estudante** no rodapé de todas as páginas.
- Ajuste endereço, telefone, e-mail e horários (páginas `contato.html` e rodapé/cabeçalho).
- As imagens em `img/` são ilustrações de exemplo: para usar fotos reais, coloque-as na pasta e altere o `src` e o `alt` de cada `<img>` em `produtos.html`.
