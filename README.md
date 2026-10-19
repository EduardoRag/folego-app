# 💸 App de Finanças Pessoais com Vibe Coding

URL: https://folego-app.lovable.app/

## Funcionalidades

- **Assistente financeiro com IA:** registre receitas e despesas utilizando linguagem natural, com identificação automática de valores, categorias e datas.
- **Gerenciamento de transações:** visualize, edite, exclua e categorize suas movimentações financeiras.
- **Dashboard financeiro:** acompanhe receitas, despesas, saldo mensal e distribuição de gastos por categoria por meio de gráficos e indicadores.
- **Metas financeiras:** crie metas de economia, registre contribuições e acompanhe o progresso até atingir o valor desejado.
- **Gerenciamento de metas via chat:** crie metas e adicione valores diretamente por meio de conversas com o assistente financeiro.
- **Análises e recomendações:** consulte seus gastos e receba sugestões de economia personalizadas com base nos registros financeiros.
- **Autenticação e privacidade:** acesso por conta individual, com proteção das informações financeiras.
- **Design Universal e acessibilidade:** interface responsiva e intuitiva, desenvolvida com foco em inclusão digital, acessibilidade e facilidade de uso.

<img width="1907" height="938" alt="image" src="https://github.com/user-attachments/assets/7b1be804-947c-4746-b032-8ec29a998c59" />


# PRD (Product Requirements Document) refinado no ChatGPT:

```markdown
# PRD — Assistente de Finanças Pessoais

## 1. Visão do produto

Criar uma aplicação web responsiva para organização de finanças pessoais, permitindo que usuários registrem despesas, receitas e metas financeiras por meio de conversas com inteligência artificial.

O objetivo é tornar o controle financeiro simples, intuitivo e acessível, especialmente para pessoas sem experiência em educação financeira.

## 2. Problema

Aplicativos financeiros tradicionais frequentemente exigem muitos formulários e registros manuais, tornando o processo cansativo e pouco intuitivo.

A solução busca simplificar essa experiência utilizando linguagem natural, automação e visualização clara das informações.

## 3. Público-alvo

Pessoas que desejam organizar suas finanças pessoais de maneira prática, independentemente de idade, habilidades ou familiaridade com tecnologia.

## 4. Funcionalidades do MVP

### Autenticação
- Cadastro e login com e-mail e senha.
- Dados financeiros privados por usuário.

### Chat financeiro com IA
- Registrar receitas e despesas em linguagem natural.
- Interpretar valores, datas, descrições e categorias.
- Solicitar confirmação antes de salvar registros.
- Permitir consultas sobre as finanças do usuário.

Exemplo: "Gastei R$ 45 com almoço hoje."

### Controle financeiro
- Categorização automática de transações.
- Histórico com filtros, edição e exclusão.
- Registro alternativo por interface visual simplificada.

### Dashboard
- Total de receitas e despesas.
- Saldo mensal.
- Gráficos de gastos por categoria.
- Transações recentes.

### Metas financeiras
- Criar metas de economia.
- Registrar contribuições.
- Acompanhar progresso e valores restantes.

### Agente financeiro
- Responder perguntas sobre gastos.
- Identificar categorias com maiores despesas.
- Oferecer sugestões de economia baseadas em dados reais.

## 5. Design Universal e UX/UI

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

## 6. Requisitos técnicos

- Aplicação web com TypeScript.
- Banco de dados PostgreSQL via Supabase.
- Autenticação segura e políticas de acesso por usuário.
- Integração com IA para interpretação de mensagens.
- Validação de dados antes da persistência.
- Cálculos financeiros realizados pelo sistema, não pela IA.
- Valores monetários armazenados em centavos inteiros.
- Proteção de chaves de API e informações sensíveis.

## 7. Telas principais

1. Login e cadastro.
2. Dashboard financeiro.
3. Chat com assistente.
4. Histórico de transações.
5. Metas financeiras.

## 8. Fora do escopo

- Integração com bancos e Open Finance.
- Importação automática de extratos.
- Investimentos.
- Pagamentos e transferências.
- Aplicativo mobile nativo.

## 9. Critérios de aceite

O MVP estará funcional quando o usuário conseguir:

- Criar uma conta e acessar seus dados com segurança.
- Registrar transações por chat ou interface visual.
- Confirmar e corrigir informações interpretadas pela IA.
- Consultar, editar e excluir transações.
- Visualizar indicadores financeiros consistentes.
- Criar e acompanhar metas.
- Receber orientações baseadas em seus registros.
- Utilizar os fluxos principais com acessibilidade e boa experiência em diferentes dispositivos.

## 10. Orientações para o Lovable

Utilize este PRD como referência principal do projeto.

Antes de implementar, apresente um plano de desenvolvimento dividido em etapas.

Implemente uma etapa por vez, priorizando funcionalidades completas, código organizado, componentes reutilizáveis e boas práticas.

Não adicione funcionalidades fora do escopo sem aprovação.

O Design Universal e a acessibilidade devem ser considerados desde a primeira implementação, não como melhorias posteriores.
```

## Reflexão

### O que funcionou bem?
O refinamento do PRD utilizando o ChatGPT funcionou muito bem, eu não precisar pedir para arrumar nada, apenas adicionei algumas funcionalidades ao assistente que pensei depois de ter enviado o PRD.

### O que não funcionou como o esperado?
Não consegui adicionar todas as funcionalidades para o assistente que eu fui pensando ao longo do desenvolvimento, pois os créditos acabaram antes.

### O que aprendeu sobre conversar com IAs?
Aprendi que se o prompt estiver muito bem refinado e bem explicado a IA irá conseguir realizar um trabalho muito bem feito e com poucos erros ou até mesmo sem erros se o prompt estiver bem estruturado.
