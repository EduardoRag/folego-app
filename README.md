# 💸 App de Finanças Pessoais com Vibe Coding

Aplicação web de organização financeira pessoal desenvolvida com o Lovable, utilizando a abordagem de Vibe Coding e um PRD (Product Requirements Document) refinado com auxílio do ChatGPT.

O projeto tem como objetivo simplificar o controle financeiro por meio de uma interface intuitiva e de um assistente com inteligência artificial, permitindo gerenciar receitas, despesas e metas financeiras utilizando linguagem natural.

**Acesse a aplicação:** https://folego-app.lovable.app/

## Funcionalidades

- **Assistente financeiro com IA:** registro de receitas e despesas por linguagem natural, com identificação automática de valores, categorias e datas.
- **Gerenciamento de transações:** visualização, edição, exclusão e categorização de movimentações financeiras.
- **Dashboard financeiro:** acompanhamento de receitas, despesas, saldo mensal e distribuição de gastos por categoria por meio de gráficos e indicadores.
- **Metas financeiras:** criação de metas de economia, registro de contribuições e acompanhamento do progresso.
- **Gerenciamento de metas via chat:** criação de metas e adição de contribuições diretamente por meio de conversas com o assistente financeiro.
- **Análises e recomendações:** consultas sobre gastos e sugestões de economia personalizadas com base nos registros financeiros.
- **Autenticação e privacidade:** acesso individual com proteção das informações financeiras.
- **Design Universal e acessibilidade:** interface responsiva e intuitiva, desenvolvida com foco em inclusão digital, acessibilidade e facilidade de uso.

## Demonstração

![Interface da aplicação](https://github.com/user-attachments/assets/7b1be804-947c-4746-b032-8ec29a998c59)

## PRD — Product Requirements Document

O desenvolvimento foi orientado por um PRD refinado com auxílio do ChatGPT, contendo a visão do produto, o problema a ser resolvido, o público-alvo, as funcionalidades do MVP e os requisitos de experiência do usuário.

O documento também estabeleceu o Design Universal como princípio obrigatório, priorizando acessibilidade, usabilidade e inclusão digital.

### PRD utilizado no desenvolvimento

<details>
<summary>Visualizar PRD completo</summary>

# PRD — Assistente de Finanças Pessoais

### 1. Visão do produto

Criar uma aplicação web responsiva para organização de finanças pessoais, permitindo que usuários registrem despesas, receitas e metas financeiras por meio de conversas com inteligência artificial.

O objetivo é tornar o controle financeiro simples, intuitivo e acessível, especialmente para pessoas sem experiência em educação financeira.

### 2. Problema

Aplicativos financeiros tradicionais frequentemente exigem muitos formulários e registros manuais, tornando o processo cansativo e pouco intuitivo.

A solução busca simplificar essa experiência utilizando linguagem natural, automação e visualização clara das informações.

### 3. Público-alvo

Pessoas que desejam organizar suas finanças pessoais de maneira prática, independentemente de idade, habilidades ou familiaridade com tecnologia.

### 4. Funcionalidades do MVP

**Autenticação**
- Cadastro e login com e-mail e senha.
- Dados financeiros privados por usuário.

**Chat financeiro com IA**
- Registrar receitas e despesas em linguagem natural.
- Interpretar valores, datas, descrições e categorias.
- Solicitar confirmação antes de salvar registros.
- Permitir consultas sobre as finanças do usuário.

Exemplo: "Gastei R$ 45 com almoço hoje."

**Controle financeiro**
- Categorização automática de transações.
- Histórico com filtros, edição e exclusão.
- Registro alternativo por interface visual simplificada.

**Dashboard**
- Total de receitas e despesas.
- Saldo mensal.
- Gráficos de gastos por categoria.
- Transações recentes.

**Metas financeiras**
- Criar metas de economia.
- Registrar contribuições.
- Acompanhar progresso e valores restantes.

**Agente financeiro**
- Responder perguntas sobre gastos.
- Identificar categorias com maiores despesas.
- Oferecer sugestões de economia baseadas em dados reais.

### 5. Design Universal e UX/UI

**O Design Universal é um requisito obrigatório e deve orientar todas as decisões do produto.**

A aplicação deve proporcionar uma experiência inclusiva, intuitiva e consistente para o maior número possível de pessoas.

Diretrizes:

- Seguir as recomendações WCAG 2.2 nível AA.
- Utilizar linguagem simples e acessível.
- Garantir navegação por teclado e compatibilidade com leitores de tela.
- Manter contraste adequado, tipografia legível e elementos interativos acessíveis.
- Criar interfaces responsivas para desktop e mobile.
- Evitar excesso de informações e interações desnecessárias.
- Fornecer feedback claro e permitir correção de erros.
- Não depender exclusivamente de cores ou elementos visuais para comunicar informações.
- Permitir realizar tarefas essenciais tanto pelo chat quanto pela interface tradicional.
- Priorizar consistência visual, previsibilidade e facilidade de aprendizado.

A estética deve ser moderna, minimalista e acolhedora, sem comprometer a acessibilidade ou a usabilidade.

### 6. Requisitos técnicos

- Aplicação web com TypeScript.
- Banco de dados PostgreSQL via Supabase.
- Autenticação segura e políticas de acesso por usuário.
- Integração com IA para interpretação de mensagens.
- Validação de dados antes da persistência.
- Cálculos financeiros realizados pelo sistema, não pela IA.
- Valores monetários armazenados em centavos inteiros.
- Proteção de chaves de API e informações sensíveis.

### 7. Telas principais

1. Login e cadastro.
2. Dashboard financeiro.
3. Chat com assistente.
4. Histórico de transações.
5. Metas financeiras.

### 8. Fora do escopo

- Integração com bancos e Open Finance.
- Importação automática de extratos.
- Investimentos.
- Pagamentos e transferências.
- Aplicativo mobile nativo.

### 9. Critérios de aceite

O MVP estará funcional quando o usuário conseguir:

- Criar uma conta e acessar seus dados com segurança.
- Registrar transações por chat ou interface visual.
- Confirmar e corrigir informações interpretadas pela IA.
- Consultar, editar e excluir transações.
- Visualizar indicadores financeiros consistentes.
- Criar e acompanhar metas.
- Receber orientações baseadas em seus registros.
- Utilizar os fluxos principais com acessibilidade e boa experiência em diferentes dispositivos.

### 10. Orientações para o Lovable

Utilize este PRD como referência principal do projeto.

Antes de implementar, apresente um plano de desenvolvimento dividido em etapas.

Implemente uma etapa por vez, priorizando funcionalidades completas, código organizado, componentes reutilizáveis e boas práticas.

Não adicione funcionalidades fora do escopo sem aprovação.

O Design Universal e a acessibilidade devem ser considerados desde a primeira implementação, não como melhorias posteriores.

</details>

## Reflexões sobre o desenvolvimento

### O que funcionou bem?

O refinamento do PRD com auxílio do ChatGPT foi fundamental para orientar o desenvolvimento. A clareza dos requisitos permitiu que o Lovable gerasse a aplicação de acordo com o que havia sido planejado, sem necessidade de solicitar correções durante a implementação inicial.

As únicas alterações realizadas foram a inclusão de funcionalidades adicionais no assistente financeiro, identificadas após o envio do PRD.

### O que não funcionou como esperado?

Durante o desenvolvimento, surgiram novas ideias de funcionalidades para o assistente financeiro. Entretanto, não foi possível implementar todas elas, pois os créditos disponíveis no Lovable se esgotaram antes da conclusão dessas melhorias.

### O que aprendi sobre a interação com IAs?

A principal aprendizagem foi compreender a importância de estruturar bem as instruções fornecidas à inteligência artificial.

Um prompt claro, detalhado e contextualizado, especialmente quando apoiado por um PRD bem definido, contribui para resultados mais alinhados às expectativas e reduz a necessidade de correções e retrabalho.

Essa experiência reforçou a importância do planejamento e da comunicação precisa ao utilizar ferramentas de IA no desenvolvimento de software.
