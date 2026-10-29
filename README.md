# 💸 Conta Fácil (GoalWise Money Compass)

Desafio de projeto da **DIO (Digital Innovation One)** para criação de um aplicativo de finanças pessoais utilizando o conceito de **Vibe Coding** com o auxílio do **Copilot Web** e do **Lovable**.

🔗 **[Acesse o Preview do App aqui](https://preview--goalwise-money-compass.lovable.app/auth)**

---

## 📱 1. Resumo do Conceito do App
O **Conta Fácil** é uma aplicação web de gestão financeira pessoal com um design minimalista e moderno, cujo grande diferencial é a integração de um assistente conversacional inteligente. Suas principais funcionalidades incluem:

* **Autenticação Simples:** Tela de login e cadastro amigável com suporte a acesso rápido via Google ou e-mail/senha.
* **Agente Financeiro Conversacional:** Um chat integrado onde o usuário pode registrar despesas e receitas usando linguagem natural (ex: *"Abasteci o carro com R$ 200"*) e consultar extratos ou balanços mensais por meio de perguntas diretas.
* **Painel de Controle (Dashboard):** Visão geral rápida do mês corrente exibindo cartões de total gasto, receitas e saldo restante ("Sobrou"), acompanhada de um gráfico histórico de gastos dos últimos 6 meses.
* **Gestão de Metas:** Ferramenta dedicada para planejar e acompanhar objetivos financeiros (como reservas de emergência), permitindo definir valores desejados e prazos.
* **Perfil e Configurações:** Área para ajustar preferências do usuário, definir o objetivo financeiro principal, gerenciar categorias de despesas de forma personalizada e encerrar a sessão.

---

## 🖼️ 2. Imagens das Telas da Aplicação

| Tela de Login | Agente Financeiro (Chat) |
| :---: | :---: |
| ![Login](https://github.com/user-attachments/assets/83b9ed8f-9b3c-49a2-bb0f-94109d81e0f1) | ![Chat](https://github.com/user-attachments/assets/5f3c4206-3bd8-4207-b5ad-48336b6b48c3) |

| Painel (Dashboard) | Metas Financeiras |
| :---: | :---: |
| ![Painel](https://github.com/user-attachments/assets/d1795825-1b01-462d-a8f6-55076ac68f56) | ![Metas](https://github.com/user-attachments/assets/bc4c7d17-0d94-4769-84b2-448c9b71cf68) |

| Perfil e Configurações |
| :---: |
| ![Perfil](https://github.com/user-attachments/assets/6136c648-5bc2-4524-af8b-fab8340960df) |

---

## 📋 3. PRD / Prompt Final Utilizado na IA

<details>
<summary><b>Clique para expandir o PRD completo gerado no Copilot Web</b></summary>

```markdown
PRD - Organizador Financeiro Conversacional
Visão do Produto
Criar um aplicativo de finanças pessoais baseado em conversação, permitindo que usuários registrem receitas, despesas e metas financeiras por meio de linguagem natural.

O objetivo é tornar o controle financeiro mais simples, intuitivo e acessível para iniciantes, eliminando a necessidade de preencher formulários complexos ou utilizar planilhas.

Princípio Norteador
Todo o produto deve seguir os princípios de Design Universal, garantindo acessibilidade, simplicidade, inclusão e uma excelente experiência para o maior número possível de usuários, independentemente de idade, experiência tecnológica ou possíveis limitações físicas, sensoriais ou cognitivas.

Problema
Muitas pessoas abandonam aplicativos de controle financeiro porque:
- Exigem cadastro manual de todas as despesas.
- Possuem interfaces complexas.
- Demandam conhecimento prévio sobre categorias financeiras.
- Não oferecem orientação personalizada para melhoria dos hábitos financeiros.

Público-Alvo
Usuários entre 18 e 45 anos que desejam organizar melhor suas finanças, não possuem conhecimento avançado em educação financeira e preferem conversar em linguagem natural em vez de preencher formulários.

Proposta de Valor
"Fale naturalmente sobre seu dinheiro e deixe o aplicativo organizar suas finanças para você."

Funcionalidades do MVP
1. Registro de Gastos por Linguagem Natural
2. Classificação Automática de Transações
3. Metas Financeiras
4. Agente Financeiro Conversacional
5. Dashboard Simplificado

Requisitos Não Funcionais
Interface responsiva mobile-first, tempo de resposta rápido, arquitetura limpa e armazenamento seguro de dados.
```
## 4. Reflexão sobre o Processo
O que funcionou bem?
Velocidade de Prototipagem: A combinação de ferramentas geradas por IA permitiu estruturar rapidamente o layout completo — desde a identidade visual em tons de verde e bege até componentes complexos como gráficos, formulários e o layout do chat.

Design e Experiência de Uso (UX): A interface ficou muito limpa, intuitiva e agradável, transmitindo a sensação de um aplicativo profissional de finanças sem exigir horas de estilização manual de CSS.

## O que não funcionou como o esperado?
Lógica de Negócio e Persistência do Chat: Alinhar para que a IA do chat realmente interprete e salve os dados no banco de dados em tempo real (evitando respostas genéricas de "não há gastos registrados" quando há expectativas de integração) exigiu iterações e ajustes finos nos comandos.

Tratamento de Estados Vazios: Garantir que as telas fizessem sentido visualmente antes de o usuário inserir os primeiros dados (como os gráficos e cartões zerados no painel) exigiu refinamentos extras para que a interface não parecesse quebrada.

## O que aprendeu sobre conversar com IAs?
O poder da especificidade: Aprendi que quanto mais detalhado e contextualizado for o comando (explicando exatamente o comportamento esperado de cada componente e qual dado deve alimentar o gráfico ou o chat), mais próximo do ideal a IA entrega o código na primeira tentativa.

Desenvolvimento Iterativo: Entendi que dialogar com a IA funciona como um processo de feedback contínuo: você constrói a base, testa visualmente, identifica o que falhou (como ajustes de layout ou regras de parsing) e orienta a IA passo a passo até o resultado ficar redondo.
