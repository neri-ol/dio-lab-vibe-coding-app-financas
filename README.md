# 💸 App de Organização de Finanças Pessoais com Vibe Coding e Neri

PRD refinado no Copilot Web:


```markdown
PRD - Organizador Financeiro Conversacional
Visão do Produto
Criar um aplicativo de finanças pessoais baseado em conversação, permitindo que usuários registrem receitas, despesas e metas financeiras por meio de linguagem natural.

O objetivo é tornar o controle financeiro mais simples, intuitivo e acessível para iniciantes, eliminando a necessidade de preencher formulários complexos ou utilizar planilhas.

Princípio Norteador
Todo o produto deve seguir os princípios de Design Universal, garantindo acessibilidade, simplicidade, inclusão e uma excelente experiência para o maior número possível de usuários, independentemente de idade, experiência tecnológica ou possíveis limitações físicas, sensoriais ou cognitivas.

Problema
Muitas pessoas abandonam aplicativos de controle financeiro porque:

Exigem cadastro manual de todas as despesas.
Possuem interfaces complexas.
Demandam conhecimento prévio sobre categorias financeiras.
Não oferecem orientação personalizada para melhoria dos hábitos financeiros.
Como consequência, o usuário perde visibilidade sobre seus gastos e tem dificuldade para desenvolver hábitos financeiros saudáveis.

Público-Alvo
Usuário Principal
Pessoas entre 18 e 45 anos que:

Desejam organizar melhor suas finanças.
Não possuem conhecimento avançado em educação financeira.
Querem uma experiência simples e prática.
Preferem conversar em linguagem natural em vez de preencher formulários.
Proposta de Valor
"Fale naturalmente sobre seu dinheiro e deixe o aplicativo organizar suas finanças para você."

O sistema funciona como um assistente financeiro pessoal capaz de:

Entender gastos e receitas descritos em linguagem natural.
Organizar automaticamente as transações.
Acompanhar metas financeiras.
Oferecer recomendações simples para economizar.
Objetivos do MVP
Objetivos de Negócio
Validar a experiência conversacional para gestão financeira.
Reduzir a fricção no registro de gastos.
Avaliar a percepção de valor do Agente Financeiro.
Medir o engajamento dos usuários com a interface de chat.
Objetivos do Usuário
Registrar gastos rapidamente.
Entender para onde seu dinheiro está indo.
Receber orientações simples para economizar.
Acompanhar sua evolução financeira.
Funcionalidades do MVP

### 1. Registro de Gastos por Linguagem Natural
Exemplos:

"Gastei R$ 45 em almoço hoje."
"Paguei R$ 120 de internet."
"Abasteci o carro com R$ 200."
O sistema deve:

Extrair o valor.
Identificar o tipo da transação.
Registrar a data.
Sugerir uma categoria automaticamente.

### 2. Classificação Automática de Transações
Categorias iniciais:

Alimentação
Transporte
Moradia
Saúde
Lazer
Educação
Compras
Outros
O usuário deverá poder editar ou corrigir categorias sugeridas.

### 3. Metas Financeiras
Permitir que o usuário crie metas como:

Economizar R$ 5.000.
Criar uma reserva de emergência.
Guardar dinheiro para uma viagem.
Apresentar:

Valor acumulado.
Valor restante.
Percentual de progresso.

### 4. Agente Financeiro
Assistente virtual responsável por:

Identificar padrões de gastos.
Sugerir oportunidades de economia.
Incentivar hábitos financeiros saudáveis.
Explicar conceitos financeiros de forma simples.
Exemplos de mensagens:

"Você gastou 20% mais com delivery neste mês."

"Se mantiver o ritmo atual de economia, poderá atingir sua meta dois meses antes do previsto."

### 5. Dashboard Simplificado
Exibir:

Gastos totais do mês.
Gastos por categoria.
Evolução mensal.
Progresso das metas financeiras.
A visualização deve ser amigável para iniciantes e evitar excesso de informações.

Jornada Principal do Usuário
Primeiro Acesso
Criar conta.
Informar principal objetivo financeiro.
Conhecer o Agente Financeiro.
Registrar a primeira transação.
Uso Diário
Registrar despesas e receitas pelo chat.
Consultar resumos financeiros.
Receber recomendações automáticas.
Revisão Mensal
Visualizar relatório financeiro.
Analisar categorias de gastos.
Revisar metas.
Ajustar comportamentos financeiros.
Principais Telas
Tela 1 - Onboarding
Boas-vindas.
Definição de objetivo financeiro.
Explicação da proposta do aplicativo.
Tela 2 - Chat Financeiro
Conversa principal.
Registro de receitas e despesas.
Consultas financeiras.
Interação com o Agente Financeiro.
Tela 3 - Dashboard
Resumo financeiro.
Indicadores principais.
Gráficos simples.
Tela 4 - Metas Financeiras
Criação de metas.
Edição de metas.
Evolução e progresso.
Tela 5 - Perfil e Configurações
Preferências do usuário.
Categorias personalizadas.
Configurações da conta.
Requisitos de Design Universal
A solução deve ser desenvolvida considerando os princípios de Design Universal.

Simplicidade e Clareza
Utilizar linguagem simples.
Evitar termos técnicos desnecessários.
Explicar conceitos financeiros quando necessário.
Priorizar fluxos intuitivos.
Legibilidade
Alto contraste entre texto e fundo.
Hierarquia visual consistente.
Fontes legíveis.
Espaçamento adequado.
Acessibilidade
Compatibilidade com leitores de tela.
Navegação por teclado.
Textos alternativos para elementos visuais.
Feedback claro para ações importantes.
Flexibilidade de Uso
Layout responsivo para celular e desktop.
Preparação para futuras interações por voz.
Navegação consistente em diferentes dispositivos.
Redução da Carga Cognitiva
Mostrar apenas informações relevantes.
Evitar excesso de gráficos ou indicadores.
Utilizar mensagens objetivas.
Priorizar recomendações acionáveis.
Requisitos Não Funcionais
Interface responsiva.
Tempo de resposta inferior a 2 segundos para interações comuns.
Design mobile-first.
Arquitetura preparada para futuras integrações financeiras.
Armazenamento seguro dos dados do usuário.
Fora do Escopo do MVP
Não desenvolver inicialmente:

Integração bancária automática.
Open Finance.
Controle avançado de cartão de crédito.
Gestão de investimentos.
Planejamento tributário.
Contas compartilhadas.
Sincronização com múltiplos usuários.
Critérios de Sucesso
O MVP será considerado validado se:

Usuários conseguirem registrar gastos sem treinamento.
Pelo menos 70% das transações forem classificadas corretamente.
Usuários realizarem mais de 5 interações financeiras por semana.
A maioria dos usuários avaliar a experiência como simples e intuitiva.
Usuários conseguirem criar e acompanhar metas financeiras sem suporte adicional.
Entregável Esperado da IA
Gerar:

Estrutura das telas.
Fluxos de navegação.
Arquitetura do sistema.
Modelo de banco de dados simplificado.
Componentes principais da interface.
Estratégia de validação do MVP.
Sugestões técnicas para implementação no Lovable.
Toda a proposta deve utilizar linguagem simples, foco educacional e boas práticas de Design Universal.
```
Interações com o lovable 
> Crie um app de finanças pessoais com base no seguinte PRD {PRD}

> Fix error

Resultado Final no Lovable: https://preview--goalwise-money-compass.lovable.app/auth

<img width="1919" height="905" alt="image" src="https://github.com/user-attachments/assets/83b9ed8f-9b3c-49a2-bb0f-94109d81e0f1" /> - tela de login

<img width="1919" height="900" alt="image" src="https://github.com/user-attachments/assets/5f3c4206-3bd8-4207-b5ad-48336b6b48c3" /> - conversa

<img width="1918" height="904" alt="image" src="https://github.com/user-attachments/assets/d1795825-1b01-462d-a8f6-55076ac68f56" /> - painel

<img width="1919" height="903" alt="image" src="https://github.com/user-attachments/assets/bc4c7d17-0d94-4769-84b2-448c9b71cf68" /> - metas

<img width="1919" height="908" alt="image" src="https://github.com/user-attachments/assets/6136c648-5bc2-4524-af8b-fab8340960df" /> - perfil


### O Conta Fácil é uma aplicação web de gestão financeira pessoal com um design minimalista e moderno, cujo grande diferencial é a integração de um assistente conversacional inteligente. Suas principais funcionalidades incluem:   Autenticação Simples: Tela de login e cadastro amigável com suporte a acesso rápido via Google ou e-mail/senha.   Agente Financeiro Conversacional: Um chat integrado onde o usuário pode registrar despesas e receitas usando linguagem natural (ex: "Abasteci o carro com R$ 200") e consultar extratos ou balanços mensais por meio de perguntas diretas.   Painel de Controle (Dashboard): Visão geral rápida do mês corrente exibindo cartões de total gasto, receitas e saldo restante ("Sobrou"), acompanhada de um gráfico histórico de gastos dos últimos 6 meses.   Gestão de Metas: Ferramenta dedicada para planejar e acompanhar objetivos financeiros (como reservas de emergência), permitindo definir valores desejados e prazos.   Perfil e Configurações: Área para ajustar preferências do usuário, definir o objetivo financeiro principal, gerenciar categorias de despesas de forma personalizada e encerrar a sessão.   

### O que funcionou bem?

Velocidade de Prototipagem: A combinação de ferramentas geradas por IA permitiu estruturar rapidamente o layout completo — desde a identidade visual em tons de verde e bege até componentes complexos como gráficos, formulários e o layout do chat.Design e Experiência de Uso (UX): A interface ficou muito limpa, intuitiva e agradável, transmitindo a sensação de um aplicativo profissional de finanças sem exigir horas de estilização manual de CSS.

### O que não funcionou como o esperado?
Lógica de Negócio e Persistência do Chat: Alinhar para que a IA do chat realmente interprete e salve os dados no banco de dados em tempo real (evitando respostas genéricas de "não há gastos registrados" quando há expectativas de integração) exigiu iterações e ajustes finos nos comandos.   Tratamento de Estados Vazios: Garantir que as telas fizessem sentido visualmente antes de o usuário inserir os primeiros dados (como os gráficos e cartões zerados no painel) exigiu refinamentos extras para que a interface não parecesse quebrada.   O que aprendeu sobre conversar com IAs?O poder da especificidade: Aprendi que quanto mais detalhado e contextualizado for o comando (explicando exatamente o comportamento esperado de cada componente e qual dado deve alimentar o gráfico ou o chat), mais próximo do ideal a IA entrega o código na primeira tentativa.Desenvolvimento Iterativo: Entendi que dialogar com a IA funciona como um processo de feedback contínuo: você constrói a base, testa visualmente, identifica o que falhou (como ajustes de layout ou regras de parsing) e orienta a IA passo a passo até o resultado ficar redondo.

