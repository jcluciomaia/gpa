# Sistema de Gestão de Produção Acadêmica (GPA)

## Sobre o Projeto
O **GPA** é um sistema desenvolvido para programas de pós-graduação stricto sensu, focado no acompanhamento, gestão e visualização da produção acadêmica de docentes e discentes. Ele oferece ferramentas para cadastro, análise de indicadores (dashboard) e exploração da rede de colaboração acadêmica.

## Arquitetura de Pastas

```text
├── data/
│   ├── estrutura_gpa.json   # Dados estruturais do programa (turma, docentes, discentes, disciplinas)
│   └── producoes.json       # Base de dados de produções acadêmicas cadastradas
├── admin.html               # (A implementar) Painel de administração
├── cadastro.html            # Interface de cadastro e gerenciamento de produções
├── index.html               # Dashboard principal com métricas e lista de produções
├── rede.html                # (A implementar) Visualização de rede de colaboração
└── README.md                # Documentação do projeto
```

## Como Usar
1. **Ambiente Local**: Basta abrir o arquivo `index.html` em qualquer navegador web moderno ou utilizar um servidor local (como `Live Server` ou `python -m http.server`).
2. **Dashboard**: Acesse `index.html` para visualizar o resumo das produções e aplicar filtros interativos por autor e tipo de publicação.
3. **Cadastro**: Acesse `cadastro.html` (ou clique no link de navegação) para inserir, editar ou remover produções. Os dados podem ser importados/exportados em formato JSON.

## Tecnologias Utilizadas
- HTML5
- CSS3
- JavaScript Vanilla

O projeto está pronto para ser hospedado via GitHub Pages ou outras plataformas de hospedagem estática.
