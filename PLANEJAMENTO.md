
# Agenda Paroquial — Planejamento do Sistema

## 1. Objetivo

Desenvolver um sistema web responsivo para divulgar eventos paroquiais e permitir que fiéis solicitem agendamentos.

O sistema será inicialmente um projeto acadêmico de Introdução à Programação Web, com possibilidade de comercialização para diferentes paróquias.

## 2. Tecnologias

### Versão inicial
- HTML5
- CSS3
- JavaScript
- Arquivos de configuração JavaScript
- Dados fictícios para testes

### Versões futuras
- Banco de dados
- Servidor para processamento de solicitações
- Autenticação e permissões de funcionários
- Integração com WhatsApp Business
- Área administrativa completa

## 3. Páginas públicas

- index.html — Calendário e eventos paroquiais
- agendar.html — Solicitação de agendamentos
- loja.html — Loja paroquial
- sobre.html — Informações da paróquia

Todas as páginas devem ser responsivas.

## 4. Formulário de agendamento

O formulário será dividido em etapas, com barra de progresso e botões Voltar e Próximo.

### Etapa 1 — Dados do fiel
- Nome completo
- Telefone/WhatsApp
- Endereço

### Etapa 2 — Tipo de agendamento
Menu de seleção com serviços cadastrados.

### Etapa 3 — Local
Seleção da igreja ou comunidade.

Quando necessário, seleção do padre responsável.

### Etapa 4 — Data e horário
- Calendário com datas disponíveis destacadas
- Aviso vermelho com breve pulsação para datas indisponíveis
- Seleção de horários permitidos
- Disponibilidade conforme serviço, local e padre

Serviços por ordem de chegada não exigem reserva individual.

### Etapa 5 — Revisão e envio
Apresentação dos dados para conferência.

Mensagem após o envio:

"Seu agendamento será analisado pela secretária. Informaremos pelo WhatsApp se o seu horário foi confirmado ou recusado."

Exibir o telefone informado pelo fiel.

## 5. Serviços

- Batismo: exige preparação dos padrinhos
- Casamento: conforme disponibilidade da igreja
- Primeira Eucaristia: exige requisitos de catequese
- Crisma: exige requisitos de catequese
- Confissão: dia e horário fixos, por ordem de chegada
- Direção espiritual: conforme agenda do padre
- Secretaria paroquial: atendimento em horário fixo, por ordem de chegada
- Intenção de missa: escolha do tipo e descrição
- Unção dos enfermos: conforme agenda do padre, com orientação para urgências
- Bênção de residência: conforme agenda do padre
- Solicitação de missa: permite escolha do padre
- Outros: campo de descrição livre

A nomenclatura e a organização dos serviços poderão ser ajustadas durante o desenvolvimento.

## 6. Locais fictícios

- Igreja Matriz São José (exemplo para teste)
- Capela Nossa Senhora de Fátima (exemplo para teste)
- Comunidade Santo Antônio (exemplo para teste)

Os locais poderão oferecer serviços e horários diferentes.

## 7. Configuração dos serviços

Os serviços serão cadastrados em arquivos JavaScript.

Cada serviço poderá definir:
- Nome e descrição
- Requisitos
- Locais permitidos
- Necessidade de escolher padre
- Dias e horários disponíveis
- Campos adicionais

Futuramente, essas configurações poderão ser alteradas pela área administrativa.

## 8. Área administrativa — futura

Acesso restrito a funcionários autorizados.

Funcionalidades:
- Visualizar solicitações pendentes
- Confirmar ou recusar agendamentos
- Gerenciar agenda dos padres
- Cadastrar e modificar serviços
- Cadastrar igrejas e comunidades
- Configurar horários e datas bloqueadas
- Gerenciar eventos paroquiais
- Gerar relatórios semanais de eventos para avisos das missas
- Baixar relatórios
- Gerar resumos de intenções de missa
- Consultar histórico de solicitações

## 9. WhatsApp

Fluxo planejado:
1. Fiel envia a solicitação.
2. Secretaria recebe a solicitação.
3. Funcionário confirma ou recusa.
4. Fiel recebe a resposta pelo WhatsApp.
5. Agendamento confirmado atualiza a disponibilidade.

A versão inicial poderá abrir uma mensagem preenchida no WhatsApp.

Automação de respostas e bloqueio compartilhado de horários dependerão de integração futura.

## 10. Evolução do projeto

### Fase 1 — Projeto acadêmico
- Interface responsiva
- Navegação entre páginas
- Formulário em etapas
- Regras demonstrativas em JavaScript
- Validação de campos
- Simulação de disponibilidade

### Fase 2 — Sistema com dados compartilhados
- Banco de dados
- Autenticação
- Área administrativa
- Controle real de horários
- Gestão dos padres
- Histórico de agendamentos

### Fase 3 — Integrações e comercialização
- Notificações pelo WhatsApp
- Confirmação automatizada
- Configurações independentes por paróquia
- Relatórios e melhorias administrativas
- Segurança e proteção de dados pessoais

## 11. Observações

- Não alterar o design aprovado sem avaliação.
- Desenvolver com responsividade desde o início.
- Priorizar aprendizado passo a passo.
- Utilizar dados fictícios durante os testes.
- Não considerar solicitações simuladas como reservas reais.
- Atualizar este planejamento conforme novas decisões.
