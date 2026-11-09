# 🐾 Patinhas Felizes – Site de Petshop (Fase 1)

Projeto da disciplina **Fundamentos de Sistemas Web**.
Site estático desenvolvido apenas com **HTML5**, sem CSS, Bootstrap ou JavaScript (que serão trabalhados na Fase 2).

**Autor:** Ramario L. Rodrigues

🔗 **Site publicado:** https://romaszw.github.io/petshop-patinhas-felizes/

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
petshop-patinhas-felizes/
├── index.html
├── produtos.html
├── servicos.html
├── contato.html
├── README.md
├── img/            # imagens dos produtos (SVG)
└── css/
    └── estilo.css  # tema branco, azul e rosa (usado na Fase 2)
```

## Como visualizar

Acesse o link do site publicado acima ou baixe os arquivos e abra o `index.html` em qualquer navegador.

## Como publicar no GitHub Pages

1. Envie todos os arquivos e pastas para um repositório no GitHub.
2. Abra **Settings → Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**, selecione a branch `main` e a pasta `/ (root)` e clique em **Save**.
4. Aguarde alguns minutos para o site ficar disponível.

## Fase 2: ativando as cores

O arquivo `css/estilo.css` já traz o tema branco, azul e rosa. Para aplicá-lo, remova os comentários da linha abaixo no `<head>` de cada página HTML:

```html
<!-- <link rel="stylesheet" href="css/estilo.css"> -->
```
