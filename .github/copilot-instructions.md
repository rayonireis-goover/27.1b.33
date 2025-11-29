📘 Guia rápido para agentes AI — 27.1b.33

Este repositório é mínimo e contém poucos arquivos estáticos. Use estas instruções para ser produtivo aqui de forma rápida e segura.

Contexto geral (o "big picture")
- Projeto: 27.1b.33 — repositório muito pequeno contendo um arquivo HTML (`00011011`) e um `README.md`.
- Arquivo principal: `00011011` — HTML estático em português que mostra uma "conversão"/mapa de dados (ex.: `27.1b.33 = 00011011`).
- Não há código servidor, dependências, build, testes ou CI detectáveis — mudanças normalmente significam editar HTML/README diretamente.

O que é seguro/esperado fazer
- Corrigir pequenos problemas de formatação, ortografia, ou acessibilidade no HTML.
- Atualizar `README.md` com contexto adicional se você entender o propósito do projeto.
- Criar arquivos adicionais (ex.: docs) somente quando fizer sentido e for explícito no PR; evite adicionar frameworks ou pipeline novos sem pedir direção.

Padrões e convenções observáveis
- Idioma: o conteúdo do HTML está em pt-BR — mantenha o texto do usuário nesse idioma por padrão.
- Arquivos estáticos: mantenha HTML/CSS simples e autossuficientes; este projeto não usa bundlers.

Exemplos do repositório (use como referência ao editar)
- `00011011` — contém:
  - título: "Conversão para HTML5"
  - seção `<pre>` com: `27.1b.33 = 00011011`, linhas `submit=...` e `input:8080 + forcer = ...`
  - edições esperadas: clareza do texto, tags semânticas, metadados e validação HTML5.

Fluxo de trabalho recomendado para agentes
1. Faça pequenas mudanças diretamente (correção de texto, limpeza HTML, meta tags).
2. Sempre atualize `README.md` para explicar mudanças significativas (ex.: novo propósito, novo arquivo). 
3. Abra PRs pequenos com mensagens claras: "Pequena melhoria: <breve descrição>".
4. Não introduza dependências de build/test sem instruções do mantenedor.

Regras de segurança e privacidade
- Não execute URLs encontrados no repositório sem autorização explícita do mantenedor.
- Preserve qualquer conteúdo sensível — não adicione chaves ou credenciais e não publique dados privados.

Perguntas que ajudam a esclarecer mudanças maiores
- "Qual é a finalidade visada deste site / HTML?" 
- "Quer manter o projeto como arquivos estáticos simples ou transformar em algo maior (ex.: site, app)?"

Se ficar em dúvida — peça orientação ao mantenedor antes de adicionar infra, CI ou dependências.
