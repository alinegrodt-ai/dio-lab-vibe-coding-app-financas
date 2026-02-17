# 💸 App de Organização de Finanças Pessoais com Vibe Coding

Este projeto trata-se de um desafio de criação de APP de finanças com VIBE CODING, utilizando o chatGPT e o Lovable, com uma comunicação simples e natural. O foco é desenvolver o conceito de um **App de Organização de Finanças Pessoais**, mas, acima de tudo, aprender o **jeito Vibe de programar com IA**.

## ✨ O que é Vibe Coding

**Vibe Coding** é uma forma leve e criativa de desenvolver com IA, baseada em **conversas naturais e bem estruturadas**. Você não precisa escrever código linha por linha. Em vez disso, aprende a **guiar a IA** descrevendo suas ideias de forma clara, com **intenção e contexto**. Em outras palavras:

> Você mostra a vibe da sua ideia e a IA transforma em solução (ou em um caminho para ela).

## 🎯 Desafio

Problema: Muitas pessoas não conseguem manter um controle financeiro porque os aplicativos exigem muita entrada de dados manual, e a criação de orçamentos é vista como algo tedioso. 

Precisamos de uma solução que permita **controlar as finanças por meio de uma conversa simples**, com **agentes de IA** capazes de criar **planos de economia personalizados e automatizados**. Você deve utilizar as ideias de **Vibe Coding** e **MVP (Produto Mínimo Viável)** para desenvolver o **conceito de um aplicativo** que resolva o problema citado.


## 🪄 Etapas do Desafio

## 🪄 Interações com o ChatGPT
Não foi possível usar o Copilot, pois solicitou inscrição paga.

O chatGPT já orientou "quebrar" o PRD em prompts para utilizar no Lovable:

PROMPT "ajude-me a revisar meu "product requirements document" abaixo, pois pretendo usá-lo no Lovable para exercitar minhas skills de vibe coding. Poderia me ajudar? Como resposta me mande o PRD revisado e sintetize de forma didática os conceitos de vibe coding e PRD pois ainda estou aprendendo sobre eles. # Contexto Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas com o usuário em linguagem natural. A ideia é facilitar o controle financeiro de forma simples e natural, sem formulários manuais ou planilhas complexas. # Problema Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e pouca personalização. Quero resolver isso com uma experiência de conversa e recomendações automáticas de economia. # Público-Alvo Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação, principalmente iniciantes. # Funcionalidades-Chave 1. Registrar gastos via chat em linguagem natural. 2. Classificar automaticamente as transações. 3. Definir e acompanhar metas financeiras. 4. Receber dicas de economia do “Agente Financeiro”. 5. Visualizar relatórios simples e personalizados. # Entregável da IA Gerar um plano de MVP com as principais telas, recursos necessários e um esboço de validação inicial. Usar tom educativo e linguagem acessível, em português."

CHAT A seguir está o PRD revisado, mais estruturado e pronto para uso no Lovable, seguido de uma explicação didática sobre PRD e vibe coding para você usar como referência no aprendizado.

CHAT Se quiser, posso te ajudar no próximo passo: transformar esse PRD em prompts ideais para o Lovable gerar o MVP.

PROMPT Poderia deixar claro que a solução deve ter um design universal, ou seja, que possa ser usado com boa experiência pelo máximo de usuários possíveis? Me explique didaticamente também o conceito de design universal.

CHAT Se quiser, posso agora transformar esse PRD em checklist de prompts estruturados para você rodar no Lovable e começar a prototipar.

PROMPT sim, transforme esse PRD em checklist de prompts estruturados para rodar no lovable

### 2. Explorando o Lovable na Prática

Utilizei os prompts sugeridos pelo ChatGPT a seguir:

✅ ETAPA 1 — Gerar o conceito do produto (alinhamento inicial)
Message

Crie a estrutura de um aplicativo mobile chamado "Agente Financeiro".

O app deve permitir que o usuário organize suas finanças pessoais conversando em linguagem natural, como se estivesse mandando mensagens.

O foco é eliminar formulários e planilhas, transformando o controle financeiro em algo simples e acessível.

Use princípios de Design Universal:

Interface extremamente simples.

Linguagem não técnica.

Boa experiência para iniciantes e pessoas com baixa familiaridade digital.

Reduzir esforço cognitivo ao máximo.

Descreva:

A proposta central do produto.

A experiência principal do usuário.

O diferencial em relação a apps financeiros tradicionais.

✅ ETAPA 2 — Definir a arquitetura das telas (UX estrutural)
Message

Desenhe a arquitetura de UX do MVP.

O aplicativo deve ter como centro uma interface conversacional.

Crie apenas as telas essenciais:

Chat principal (registro e interação).

Resumo financeiro simples.

Metas financeiras.

Histórico de transações.

Configurações mínimas.

Evite dashboards complexos.
Evite tabelas.
Evite excesso de informação.

Explique o papel de cada tela e o que deve aparecer nela.

✅ ETAPA 3 — Definir o comportamento conversacional da IA
Message

Modele o comportamento do "Agente Financeiro".

Ele deve:

Entender frases naturais como:
"Gastei 30 reais no almoço"
"Recebi meu salário"
"Quero economizar esse mês"

Extrair automaticamente:

Valor

Tipo (receita ou despesa)

Categoria

Data

O agente deve responder de forma educativa, leve e não julgadora.

Forneça exemplos reais de diálogo entre usuário e sistema.

✅ ETAPA 4 — Criar a lógica de categorização automática
Message

Defina a lógica inicial de categorização automática de transações.

Crie categorias simples:

Alimentação

Transporte

Moradia

Lazer

Saúde

Outros

O sistema deve sugerir categorias automaticamente e permitir correção fácil.

Explique como lidar com:

Ambiguidade de texto

Erros de digitação

Falta de informação

✅ ETAPA 5 — Projetar o sistema de metas financeiras simples
Message

Projete a funcionalidade de metas financeiras baseada em conversa.

O usuário pode dizer:
"Quero guardar 200 reais por mês"
"Quero parar de gastar com delivery"

O sistema deve:

Criar metas automaticamente.

Mostrar progresso visual simples.

Enviar mensagens de acompanhamento leves.

Nada de gráficos complexos.

✅ ETAPA 6 — Definir os insights automáticos (inteligência do produto)
Message

Crie o modelo de geração de insights financeiros automáticos.

Os insights devem:

Ser curtos.

Ser compreensíveis por qualquer pessoa.

Não usar termos técnicos.

Ajudar o usuário a perceber hábitos.

Exemplo de tom:
"Você gastou mais com transporte esta semana. Quer acompanhar isso?"

Forneça exemplos de regras simples que geram esses insights.

✅ ETAPA 7 — Garantir aplicação prática de Design Universal
Message

Revise toda a experiência do app aplicando Design Universal.

Garanta:

Baixa carga cognitiva.

Interface limpa.

Poucas decisões por tela.

Textos curtos.

Tolerância a erro do usuário.

Uso confortável em celular.

Liste ajustes necessários para tornar o produto realmente inclusivo.

✅ ETAPA 8 — Definir regras técnicas mínimas (sem overengineering)
Message

Descreva apenas a estrutura técnica necessária para o MVP funcionar.

Incluir:

Interpretação de linguagem natural.

Armazenamento de transações.

Motor simples de categorização.

Geração de respostas conversacionais.

Evitar:

Integrações bancárias.

Open Finance.

Funcionalidades complexas.

Foco total em validação rápida.

✅ ETAPA 9 — Criar plano de validação do MVP
Message

Crie um plano de validação do MVP com usuários reais.

Definir:

O que medir nas primeiras semanas.

Como saber se a experiência conversacional funciona.

Indicadores de sucesso.

Sinais de que o produto precisa mudar.

Priorizar aprendizado, não escala.

_______________________

Após, fiz alguns ajustes finais, solicitei ao chatGPT a criação de um nome divertido (o escolhido foi ConteComigo) e de um ícone.
Por fim, solicitei a publicação do APP.


### 3. Entregando o Desafio na DIO

https://conte-comigo-fique-rico.lovable.app


## 💬 Conclusão

Foi muito divertido e esclarecedor esse projeto, contudo, acabei assinando o Lovable, pois não foi possível finalizar o projeto com apenas 5 interações.
