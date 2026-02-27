# 💸 App de Organização de Finanças Pessoais do Jonathas Vargas com Vibe Coding

Este é um trabalho foi desenvolvido como um desafio de projeto da DIO ao estilo Vibe Code, utilizando o Copilot e o Lovable, com o intuito de criar um aplicativo de organização financeira pessoal, baseado em interações em linguagem natural.

PRD Refinado no copilot:

```Markdown
PRD – Aplicativo de Organização Financeira Conversacional com Design Universal

1. Contexto
O projeto visa criar um aplicativo de Organização de Finanças Pessoais baseado em conversas, permitindo registrar gastos, acompanhar metas e receber recomendações usando linguagem natural. O objetivo é tornar o controle financeiro simples, intuitivo e acessível para iniciantes, eliminando a necessidade de planilhas ou formulários complexos.

2. Problema
A maioria dos aplicativos financeiros exige lançamentos manuais extensos e interfaces complexas, o que desmotiva especialmente usuários iniciantes. Faltam soluções que ofereçam simplicidade, personalização, interação natural e acessibilidade ampla.

3. Público-Alvo
Pessoas que desejam iniciar ou retomar o controle financeiro de forma prática e descomplicada, especialmente iniciantes ou usuários que abandonaram apps tradicionais devido à complexidade.

4. Proposta de Valor
Criar um assistente financeiro conversacional capaz de registrar gastos, organizar categorias, sugerir metas e fornecer dicas de economia por meio de interações simples, naturais e acessíveis ao máximo de pessoas possível.

5. Design Universal (Requisito Obrigatório)
A solução deve adotar Design Universal, garantindo que o aplicativo seja utilizável de forma confortável, eficiente e intuitiva pelo maior número possível de usuários, independentemente de idade, experiência digital ou limitações físicas ou cognitivas.

Exemplos de aplicação no projeto:
- Interface visual com alto contraste e elementos claros.
- Navegação totalmente operável via chat e comandos simples.
- Compatibilidade com leitores de tela.
- Tamanho de texto ajustável.
- Linguagem simples e livre de jargões técnicos.
- Fluxos projetados para funcionarem bem para iniciantes, idosos ou pessoas com pouca familiaridade digital.

6. Funcionalidades-Chave
1. Registro de gastos via chat em linguagem natural.
2. Classificação automática das transações.
3. Criação e acompanhamento de metas financeiras.
4. Agente Financeiro para dicas de economia.
5. Relatórios simples, personalizados e acessíveis, incluindo resumos em linguagem natural.

7. Entregável esperado da IA (Lovable)
A IA deve gerar:
- Plano de MVP com funcionalidades essenciais.
- Wireframes das principais telas, respeitando princípios de Design Universal.
- Lista de recursos técnicos necessários (ex.: NLP, backend, banco de dados, UI).
- Estratégia de validação inicial com testes de usabilidade para diferentes perfis de usuários.
- Conteúdo com tom educativo, claro e acessível, em português.

8. Explicação Didática: O que é Design Universal
Design Universal é o conceito de projetar produtos, serviços e ambientes para serem utilizáveis pelo maior número de pessoas possível, desde o início, sem necessidade de adaptações posteriores. Ele busca inclusão, simplicidade e usabilidade em diferentes contextos.

Aplicado a aplicativos:
- textos legíveis,
- comandos claros,
- interação acessível por voz ou leitura,
- navegabilidade intuitiva,
- compatibilidade com tecnologias assistivas.

9. Explicação Didática: O que é Vibe Coding
Vibe Coding é uma abordagem de desenvolvimento guiada por IA em que o criador descreve a intenção, a sensação e o comportamento desejado do produto, em vez de instruções técnicas detalhadas. A IA transforma essa "vibe" em código, interface e fluxo. É ideal para prototipagem rápida, criatividade e iterações fluídas.

Exemplos:
- "Quero um visual leve e minimalista."
- "A experiência deve parecer uma conversa natural com um assistente financeiro."
- "O design deve ser acessível, claro e acolhedor."

Fim do documento.
```

Interações com o Lovable:
> Olá, Lovable! Crie um app de finanças pessoais com base no seguinte PRD (Documento de Requisitos de Produto): {PRD}

> O que percebi foi que não tem controle de acesso, utilizando login e senha para que exista segurança ao usuário, podendo ser utilizado o recurso da conta do Google. Poderia fazer isso?

> Submitted "Enable Cloud" (Para adicionar login com email/senha e Google, preciso primeiro ativar o Lovable Cloud (nosso backend integrado). Fazer isso agora?)

> Sim, com perfil (Perfil de usuário?)

> Configure o login com Google para que os usuários possam entrar com a conta Google. (⚠️ Para o login com Google funcionar, é necessário configurar o provedor OAuth no Lovable Cloud. Deseja que eu configure isso agora?)

> Adicione uma página de recuperação de senha.

Resultado final: https://conversational-finance-friend.lovable.app

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/3df033ff-cef5-42a1-8a45-25c9947534cf" />

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/d6e36ba9-e22a-492e-b71e-57bf9918d4a2" />

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/7ef52a00-fc93-46c5-8338-e9435d90c9c9" />


# 📱 Conversational Finance Friend

Aplicativo de **Organização de Finanças Pessoais** baseado em interação por linguagem natural.  
O objetivo é simplificar o controle financeiro, tornando-o acessível e amigável para iniciantes.

---

## 🚀 Funcionalidades Principais

### 1. Conversa e Registro
- Registro de gastos via **chat em linguagem natural**.  
- Interação com o **Agente Financeiro**, que atua como guia educativo e motivador.

### 2. Organização Automática
- **Classificação automática** das transações em categorias (moradia, alimentação, transporte, etc.).  
- Sugestões e dicas personalizadas de economia.

### 3. Metas e Planejamento
- Definição e acompanhamento de **metas financeiras**.  
- Visualização clara do progresso em relação às metas.

### 4. Relatórios e Dashboard
- **Resumo financeiro** com saldo, receitas e despesas.  
- **Relatórios por categoria** de gastos.  
- Histórico dos **últimos lançamentos**.  
- Navegação simples com abas: Conversa, Lançamentos, Metas.

### 5. Experiência do Usuário
- Interface amigável e acessível em português.  
- Tom educativo e linguagem clara.  
- Integração com **Lovable** para prototipagem rápida e edição colaborativa.

---

## 📚 Conceitos Fundamentais

### PRD (Product Requirements Document)
- Documento que descreve **o que será construído**, **por que** e **para quem**.  
- Estrutura típica: contexto, problema, público-alvo, funcionalidades, métricas de sucesso, riscos e cronograma.  
- Serve como guia para alinhar equipes de produto, design e engenharia.

### Vibe Coding
- Abordagem criativa de programação e design que foca na **sensação e experiência** do usuário.  
- Mistura lógica técnica com **design de interação** e **linguagem natural**.  
- O objetivo é criar não apenas funcionalidades, mas também uma **vibe** positiva e envolvente.  
- Exemplo: transformar um app de finanças em um **companheiro conversacional** que motiva e educa.

---

## 🎯 MVP (Minimum Viable Product)

- **Telas principais**: Chat, Dashboard, Metas, Relatórios.  
- **Recursos essenciais**: Registro de gastos, classificação automática, metas, relatórios simples.  
- **Validação inicial**: Testes com usuários iniciantes para coletar feedback sobre clareza, usabilidade e motivação.  

## Reflexão

### O que funcionou bem?
O refinamento utilizando o Copilot ajudou muito, dada as interações sem limites, pois os créditos do Lovable são limitados.
    
### O que não funcionou como o esperado?
As interações limitadas com o Lovable deixam a desejar, porém, seguindo o valioso passo-a-passo do Venilton, a quantidade de interações com o Lovable foram suficientes.

### O que aprendeu sobre conversar com IAs?
Aprendi que é basicamente uma conversa por chat com alguém, sendo que quanto melhor e mais refinado é o seu comando, melhor fica a interação e principalmente o resultado.
