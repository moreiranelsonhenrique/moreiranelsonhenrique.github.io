# Guia de manutenção do portfólio

## Estrutura

```text
/
├── index.html
├── README.md
├── README-MANUTENCAO.md
├── css/
│   └── style.css
├── projetos/
│   ├── modelo.html
│   ├── grendene.html
│   ├── mcdonalds.html
│   └── contoso.html
└── assets/
```

## Como adicionar um novo projeto

### 1. Criar a página

Dentro de `projetos/`:

1. Copie `modelo.html`.
2. Renomeie a cópia, por exemplo, para `empresa-x.html`.
3. Edite o conteúdo da cópia.

Os projetos existentes não precisam ser alterados.

### 2. Adicionar imagem ou GIF

Coloque o arquivo em `assets/`.

Exemplo:

```text
assets/empresa-x.gif
```

Na página do projeto, use:

```html
<img src="../assets/empresa-x.gif">
```

### 3. Adicionar o link do Power BI

Na página do novo projeto, substitua o link do dashboard pelo link correspondente.

### 4. Adicionar o card à página inicial

Abra `index.html`.

Copie um dos cards de projeto existentes e altere:

- título;
- imagem;
- resumo;
- link para a página do projeto;
- link do Power BI.

Mantenha as classes existentes para preservar o visual.

### 5. Testar localmente

Antes de publicar:

1. Abra `index.html` no navegador.
2. Abra o novo projeto.
3. Teste a imagem/GIF.
4. Teste `Acessar Dashboard`.
5. Teste `Ver projeto`.
6. Teste `Voltar aos projetos`.
7. Confira também em uma janela estreita/celular.

### 6. Publicar

Depois do teste, envie os arquivos alterados para o repositório:

`moreiranelsonhenrique.github.io`

## O que evitar alterar

Sem necessidade, não altere:

- `css/style.css`;
- classes existentes;
- estrutura dos projetos já publicados;
- caminhos dos arquivos existentes em `assets/`;
- regras de responsividade.

Se uma alteração exigir isso, faça uma cópia de segurança primeiro.

## Regra prática

Para um novo projeto, normalmente você trabalhará em:

```text
1. projetos/novo-projeto.html
2. assets/novo-projeto.gif
3. index.html
```

## Modelo

`projetos/modelo.html` é a base para novos projetos.

Sempre que possível, copie o modelo em vez de copiar um projeto já publicado.
