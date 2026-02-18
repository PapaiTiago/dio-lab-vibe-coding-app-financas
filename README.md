# 💸 App de Organização de Finanças Pessoais - FinChat Lovable - PapaiTiago

- PRD Refinado no ChatGPT
```text
Crie um app de Finanças Pessoais com base no seguinte PRD: PRD COMPLETO - APP DE FINANCAS PESSOAIS POR CONVERSA (COM DESIGN UNIVERSAL) Produto (nome provisório): FinChat Versao: MVP v1 Plataforma: Mobile-first (funciona bem no celular) Idioma: Portugues (Brasil) Moeda: BRL (R$) Observacao: Nao e aconselhamento financeiro. Foco em organizacao, habitos e educacao financeira.

RESUMO DO PRODUTO FinChat e um app simples de financas pessoais que permite registrar gastos e receitas em linguagem natural (chat), classificar automaticamente, acompanhar metas e ver resumos claros. O diferencial e reduzir burocracia: em vez de formularios e planilhas, o app funciona como uma conversa rapida com confirmacoes e botoes de acao (chips).

PROBLEMA E OPORTUNIDADE Problema:

Apps exigem muita digitacao, muitos campos e telas complexas.
Usuarios iniciantes desistem cedo por friccao e falta de personalizacao. Oportunidade:
Chat + chips reduzem atrito, criam habito e entregam valor rapido (primeiro registro + primeiro resumo).
OBJETIVOS DO MVP Objetivos:
Valor em 5 minutos: registrar 1 transacao e ver um resumo simples.
Registro sem esforco: linguagem natural + chips + confirmacao curta.
Confianca: quando houver duvida, o app pergunta; corrigir e facil (1 toque).
Acessibilidade (Design Universal): utilizavel por pessoas com diferentes habilidades e contextos. Nao-objetivos (fora do MVP):
Integracao bancaria/Open Finance.
Investimentos, planejamento avancado e dividas complexas.
Relatorios avancados/dashboards pesados.
IA sofisticada alem do necessario (priorizar utilidade e clareza).
PUBLICO-ALVO E PERSONAS Publico-alvo:
Iniciantes que querem organizacao pratica e sem complicacao. Personas:
Comecando agora: quer entender para onde vai o dinheiro; pouca paciencia para configuracao.
Rotina corrida: quer registrar em 10-20 segundos; valoriza atalhos e repeticao. Necessidades de acessibilidade (transversais):
Baixa visao: fonte maior e alto contraste.
Limitacao motora: alvos grandes e poucos toques.
TDAH/ansiedade: previsibilidade e pouco ruido.
Baixa alfabetizacao digital: orientacao simples e estados vazios didaticos.
DESIGN UNIVERSAL (REQUISITOS) Principios aplicados:
Uso equitativo: funcionalidades importantes funcionam por texto e por chips.
Flexibilidade: registrar por texto; corrigir por toque; revisar no historico.
Simplicidade: poucos passos, microcopy curto, telas previsiveis.
Informacao perceptivel: contraste, hierarquia visual, suporte a leitor de tela.
Tolerancia a erro: confirmacoes, desfazer, editar facil, validacoes amigaveis.
Baixo esforco: alvos grandes, poucos campos, evitar digitacao longa.
Espaco adequado: layout arejado, sem elementos pequenos. Acessibilidade minima do MVP:
Suporte ao tamanho de fonte do sistema e layout responsivo.
Contraste adequado entre texto e fundo.
Alvos de toque grandes (chips/botoes confortaveis).
Compatibilidade com leitores de tela (rotulos/aria-labels).
Ordem logica de foco na navegacao.
Mensagens de erro claras e recuperaveis.
Nao depender apenas de cor para indicar estados (usar texto/icone).
Evitar animacoes excessivas; respeitar reduzir movimento (se possivel).
ESCOPO FUNCIONAL (PRIORIDADES) P0 (obrigatorio):
Chat para registrar gasto/receita em linguagem natural.
Confirmacao do entendimento (valor, categoria, data).
Categorizacao automatica simples + pergunta quando incerto.
Historico de transacoes (listar, editar, excluir).
Resumo simples do mes (gastos, receitas, saldo simples, top categorias).
Metas simples (criar, ver progresso, atualizar manualmente no MVP).
Configuracoes basicas (categorias ativas, frequencia de dicas, privacidade).
Estados vazios e onboarding leve (ensinar o primeiro passo). P1 (importante):
Sugestoes de transacoes recorrentes (atalhos).
Exportacao de dados (CSV simples).
Lembrete gentil (opt-in). P2 (futuro):
Voz/ditado e foto de recibo.
Orcamento por categoria (limites).
Integracao bancaria.
Insights avancados e previsoes.
JORNADAS (FLUXOS PRINCIPAIS) Fluxo A - Primeiro dia (ativacao em 5 min):
Boas-vindas -> escolher objetivo (ex: controlar gastos)
Chat mostra exemplos + chip "Registrar gasto"
Usuario envia "Gastei 35 no almoco"
App confirma e salva
App mostra "Resumo do mes" (cards) + 1 dica curta Fluxo B - Rotina:
Usuario digita gasto/receita
App categoriza e confirma
Se duvida: pergunta categoria sugerida com botoes Sim/Nao
Atualiza resumo Fluxo C - Meta:
Usuario "Quero juntar R$ 1000"
App pergunta prazo (opcional)
Cria meta + mostra progresso
Sugere acao simples (educativa, sem impor)
TELAS DO MVP (6 TELAS) Tela 1 - Boas-vindas/Onboarding leve Objetivo: levar ao primeiro registro sem friccao Componentes:
Titulo curto
2-3 perguntas por chips (ex: controlar gastos / gastos+receitas)
Toggle "Receber dicas?" com explicacao
Botao "Comecar" Estado vazio: exemplos de mensagens Acessibilidade: texto grande, leitura por leitor de tela, linguagem simples
Tela 2 - Chat (nucleo) Objetivo: registrar e orientar Componentes:

Campo de mensagem
Chips: Registrar gasto, Registrar receita, Ver resumo, Criar meta
Bolhas de conversa com confirmacoes Estados:
Sem dados: exemplos + sugestoes
Erro: mensagem clara + botao tentar novamente Acessibilidade: foco no input, rotulos claros, mensagens curtas
Tela 3 - Transacoes (historico) Objetivo: revisar e corrigir facilmente Componentes:

Lista por data
Filtros simples (mes, categoria)
Acoes: editar, excluir Acessibilidade: botoes grandes, confirmacao de exclusao com desfazer
Tela 4 - Metas Objetivo: acompanhar progresso Componentes:

Cards de metas (alvo, atual, progresso)
Botao "Nova meta" Acessibilidade: progresso tambem em texto (nao so por cor)
Tela 5 - Resumo (relatorios simples) Objetivo: clareza rapida Componentes (cards):

Gastos do mes
Receitas do mes
Saldo simples
Top categorias Acessibilidade: numeros bem formatados, evitar graficos complexos no MVP
Tela 6 - Configuracoes Objetivo: controle e confianca Componentes:

Frequencia de dicas / desligar
Categorias ativas (toggles)
Privacidade: exportar dados / apagar dados Acessibilidade: descricoes curtas e objetivas
UX DE CONVERSA (ESPECIFICACAO) Intencoes P0 (intents):
Registrar gasto
Registrar receita
Ver resumo
Ver historico
Criar meta
Corrigir categoria/valor/data
Ajuda (como registrar) Entidades P0:
valor, data, categoria, descricao, tipo Padrao de resposta do app:
Confirmar entendimento em 1-2 linhas
Se duvida: perguntar com botoes
Finalizar com acao rapida (Ver resumo, Editar) Exemplo: Usuario: "paguei 47 na farmacia" App: "Anotei R$ 47 em Saude (hoje). Confirma?" [Sim] [Trocar categoria]
AGENTE FINANCEIRO (DICAS) Tom:
Educativo, neutro, sem culpa e sem julgamento Regras:
Dicas curtas e acionaveis
Sempre opcao de dispensar ("nao agora")
Evitar "voce deveria"; preferir "uma ideia e" Gatilhos simples (MVP):
Categoria acima do padrao da semana
Meta parada
Sem registros por 3 dias (apenas se opt-in) Frequencia:
Maximo 1 dica por dia no MVP
CATEGORIZACAO AUTOMATICA (MVP) Categorias iniciais (8-10):
Alimentacao
Mercado
Transporte
Moradia
Contas (agua/luz/internet)
Saude
Lazer
Educacao
Roupas/Compras
Outros Regras:
Palavras-chave (ex: uber -> Transporte; farmacia -> Saude)
Estabelecimentos comuns (se digitados)
Se confianca baixa: perguntar confirmacao Aprendizado com correcoes:
Se usuario trocar categoria, salvar preferencia para aquele termo/estabelecimento
REQUISITOS FUNCIONAIS (RF) E CRITERIOS RF-01 Registrar transacao via chat
Aceitar texto natural com valor + descricao (+ data opcional) Criterios:
"Gastei 35 no almoco" salva gasto 35, categoria Alimentacao, data=hoje
Se faltar valor: perguntar "Qual foi o valor?" RF-02 Confirmar quando houver incerteza
Se confianca < limiar, perguntar categoria com botoes RF-03 Editar/Excluir transacao
Editar valor, categoria, data, descricao
Excluir com opcao desfazer RF-04 Resumo mensal
Mostrar total gastos, total receitas, saldo simples e top categorias RF-05 Metas
Criar (nome, valor alvo, prazo opcional)
Atualizar valor atual (manual no MVP)
Mostrar progresso RF-06 Dicas do agente
Gatilhos simples, opt-in, max 1/dia
MODELO DE DADOS (MINIMO) Transaction:
id, type (expense/income), amount, date (ISO), categoryId, description, confidence, createdAt, updatedAt Category:
id, name, keywords (lista), isActive Goal:
id, title, targetAmount, currentAmount, dueDate (opcional), createdAt UserPrefs:
currency (BRL), tipsEnabled, tipsFrequency, accessibilityPrefs (opcional)
REQUISITOS NAO-FUNCIONAIS Desempenho:
Resposta rapida ao salvar e ao abrir resumo Confiabilidade:
Mensagens claras em falhas + tentar novamente Privacidade:
Minimizar dados coletados
Exportar/apagar dados Acessibilidade:
Fonte do sistema, contraste, leitor de tela, foco, alvos grandes, erros recuperaveis
METRICAS E ANALYTICS Metricas:
Ativacao: registrou 1a transacao no D0
Aha: viu Resumo apos registrar
Retencao: registrou em 3 dias diferentes na semana 1
Confianca: taxa de correcao de categoria (deve cair com o tempo)
Engajamento util: transacoes por semana Eventos (exemplos):
onboarding_completed
transaction_created (type, category, confidence)
transaction_corrected
summary_viewed
goal_created
tip_shown / tip_dismissed
VALIDACAO INICIAL (2 SEMANAS) Hipoteses:
Usuario registra em ate 20s sem frustracao
Resumo simples aumenta valor percebido
Confirmacao aumenta confianca Testes:
Usabilidade com 5-8 iniciantes
Concierge MVP (simular agente por 3 dias com 3-5 pessoas)
Protótipo funcional medindo tempo e correcoes Criterios de sucesso (exemplo):
Ativacao >= 60%
Aha >= 40%
Tempo medio de registro <= 20s apos aprender 1 vez
ROADMAP SUGERIDO (6-8 SEMANAS) Semana 1: telas base + navegacao + onboarding Semana 2: chat + criar transacoes Semana 3: historico + editar/excluir + estados vazios Semana 4: resumo mensal + regras simples de categoria Semana 5: metas Semana 6: dicas do agente + preferencias + privacidade Semana 7-8: testes com usuarios + ajustes de acessibilidade + refinamento

RISCOS E MITIGACAO

Interpretacao errada: confirmar quando incerto; editar facil; desfazer
Falta de habito: chips + retorno imediato (resumo apos salvar) + lembrete opt-in
Escopo crescendo: manter IN/OUT firme; so adicionar apos validacao
Acessibilidade esquecida: checklist por tela + teste com leitor de tela
DEFINICAO DE PRONTO (DoD)
Registrar gasto/receita via chat com confirmacao
Editar/excluir no historico com desfazer
Resumo mensal por cards funcionando
Metas criadas e exibidas
Dicas configuraveis e nao invasivas
Checklist de acessibilidade aplicado (fonte, contraste, leitor de tela, alvos grandes, erros claros)
```

- Iterações com o Lovable;
  - PRD Completo;
  - "Eu escrevi o seguinte: "recebi 12 mil de salario" como receita. O chat me retornou pedindo para categorizar entre: alimentação, mercado, transporte ou moradia. 1 - não é despesa e sim receita, então reveja esta questao. Também o sistema entendeu ser R$ 12,00, quando 12 mil é R$ 12.000,00. Ajuste isso.";
  - "Escrevi: "Gastei 112,00 de gás. 160,00 de mercado e 75,00 de mercado" e ele me retornou: "Anotei: gasto de R$ 112,00 em Mercado (hoje). Confirma?". Ocorre que eu informei 3 despesas e ele leu somente uma. Ajuste e faça isso também nas receitas, para que ele aceita multiplas informações em 1 linha.";
  - Publicação no Link: https://finchatpapaitiago.lovable.app/;

- Prints do resultado do App publicado com auxilio de IA (ChatGPT e Lovable);
  - Resultado página inicial: <img width="1365" height="606" alt="image" src="https://github.com/user-attachments/assets/fbe6cf89-8449-401f-9db4-a5ea23051e4d" />
  - Resultado página 2: <img width="1360" height="604" alt="image" src="https://github.com/user-attachments/assets/356a7b07-f13b-4855-9aba-c2f912f3d968" />
  - Resultado página 3: <img width="1360" height="606" alt="image" src="https://github.com/user-attachments/assets/5f119dd4-9463-4135-826e-153db78169ba" />
  - Resultado página 4: <img width="1351" height="601" alt="image" src="https://github.com/user-attachments/assets/59f67062-1d60-4228-b79d-82f677f3acb7" />

- Um resumo do que **App FinChat** faz;

# 💬 FinChat

O **FinChat** é um aplicativo de controle financeiro com uma proposta inovadora: transformar a gestão das suas finanças em uma experiência de conversa simples e intuitiva.

## ✨ Funcionalidades

- **Interface em formato de chat**  
  Interaja com suas finanças como se estivesse conversando com alguém, sem a complexidade de planilhas ou dashboards tradicionais.

- **Simplicidade e acessibilidade**  
  Controle financeiro sem burocracia, pensado para quem busca praticidade no dia a dia.

- **Acesso rápido**  
  Um clique em **"Começar"** e você já inicia sua jornada financeira, sem configurações complicadas.

- **Design minimalista**  
  Interface limpa e objetiva, com foco total na experiência de conversa.

## 🎯 Objetivo

O FinChat foi criado para tornar o **controle financeiro mais humano e natural**, ajudando você a acompanhar gastos e metas de forma leve e contínua.

## 🚀 Como usar

1. Acesse o app: [FinChat](https://finchatpapaitiago.lovable.app/chat)  
2. Clique em **Começar**  
3. Converse com suas finanças e simplifique sua gestão!

---

Feito com ❤️ por Tiago

- Uma breve **reflexão sobre o processo**:
  - O que funcionou bem?
    - A interação com a IA, que direcionou o projeto para o lado que realmente eu queria;
    - O resultado do Lovable, que, mesmo com créditos limitados, conseguiu gerar uma versão utilizável e com poucos bug´s.  
  - O que não funcionou como o esperado?
    - O limite do Lovable, deixa o app pronto até certo ponto;
    - Talvez, utilizando uma versão paga, ou outro App, poderia deixar o App ainda melhor, mas isto deve acontecer com o tempo.
  - O que aprendeu sobre conversar com IAs?
    - Elas são objetivas, e respondem aos comandos;
    - Elas conseguem "ver depois da curva", guiando o usuário pelo caminho;
    - Elas não substituem o humano, porém elas potencializam o resultado;

