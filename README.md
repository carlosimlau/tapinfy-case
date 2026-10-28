# Tapinfy

**Página, agenda e clientes no mesmo lugar. Para barbearias e negócios de serviços.**

`2025` · `Produto próprio` · 🟢 Em produção · [tapinfy.co](https://www.tapinfy.co/)

---

## O problema

Numa barbearia, o agendamento chega por mensagem e o atendimento para para responder. As comissões vão pro papel. O barbeiro chega no fim da semana sem saber quanto fez. E o link da bio, quando existe, leva a uma lista de links que não agenda nada.

As agendas online resolvem o horário, mas a página é delas, com a marca delas. Um site próprio é do dono, mas custa e demora. O Instagram mostra e não agenda: é uma vitrine sem porta.

## O que construí

30 funcionalidades num plano único, sem features bloqueadas.

### Página

- Subdomínio próprio (`nome.tpfy.app`) ou domínio do cliente
- Perfil da casa: foto, nome, apresentação e todos os links num só lugar
- Catálogo de serviços com preços, duração e CTA por serviço
- Galeria de trabalhos
- 6 templates e 96 paletas visuais
- PWA: o cliente salva a página na tela do celular
- QR Code dinâmico: imprime uma vez, a página muda, o código continua certo
- Cartão de contato salvo num toque

### Agenda

- O cliente agenda sozinho: serviço, barbeiro, dia e hora
- Horários livres em tempo real na própria página
- Cada serviço com duração e preço por profissional
- Anti double-booking
- Intervalo configurável entre agendamentos
- Upsell de produtos e add-ons no momento do agendamento
- E-mail de confirmação e lembrete, com Google Calendar e `.ics`
- Visões de dia, semana e lista
- Arrastar para reagendar
- O cliente cancela e remarca sozinho
- Cada barbeiro com a sua agenda; o dono vê a casa toda
- Várias lojas num só painel
- Comissão por barbeiro calculada automaticamente

### Clientes

- Ficha por cliente: visitas, gastos, serviços feitos, faltas e última visita
- Registro de presenças, faltas e cancelamentos
- Filtros: VIP, inativos, maiores gastos, mais faltas
- Formulário de contato com até 10 perguntas personalizadas
- Portal do cliente: entra, vê o histórico e remarca sozinho
- Consentimento e conformidade com LGPD e RGPD
- A base é do dono, exportável a qualquer momento

### Dados

- Analytics de visitas, cliques, conversões e CTR
- Fontes: link direto, QR Code e campanhas
- Geolocalização por país e cidade
- Pixels Meta, GA4 e Google Ads integrados
- Atribuição: qual anúncio trouxe o cliente

### Migração e operação

- Implementação feita pela equipe: página, catálogo, agenda e equipe configurados
- Migração da base de clientes a partir de CSV ou Excel, com limpeza e duplicados identificados
- 30 dias de acompanhamento após a entrega
- Suporte incluído na assinatura

## Modelo

O modelo comercial vigente é uma subscrição de €29/mês (IVA incluído), 
sem implementação obrigatória, com a IA a montar a página a partir de Instagram/site/tabela de preços. 
Existe opção de setup com especialista a partir de €299 (pagamento único).Inclui 1 loja e 1 profissional. 
Cada profissional extra €8/mês, cada loja extra €10/mês. Venda feita por consultores comerciais.

## Em produção

| | |
|---|---|
| Agendamentos criados | 7.169 |
| Agendamentos concluídos | 6.083 |
| Clientes diferentes atendidos | 3.504 |
| Fichas migradas do sistema anterior | 11.000+ |
| E-mails automáticos de confirmação e lembrete | 13.244 |
| Registros de auditoria | 15.554 |
| Lojas na mesma conta | 4 |

Números de uma rede de barbearias com 4 lojas e 25 colaboradores, nos primeiros meses de operação. Mais de 3.000 agendamentos por mês.

## Stack

`Next.js` `React` `TypeScript` `Tailwind`

## Meu papel

Produto, UX, arquitetura, implementação e deploy. Sozinho, do zero até produção.

---

O código do produto é privado. Este repositório é a apresentação do case.

[![carlosimlau.com](https://img.shields.io/badge/carlosimlau.com-9EFD38?style=for-the-badge&logo=googlechrome&logoColor=111113&labelColor=9EFD38&color=9EFD38)](https://www.carlosimlau.com/)
[![tapinfy.co](https://img.shields.io/badge/ver%20o%20produto-C6C5C9?style=for-the-badge&labelColor=292929&color=292929)](https://www.tapinfy.co/)
