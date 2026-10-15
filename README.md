# CRM do Corretor

**Um CRM de código aberto para o corretor de imóveis autônomo, feito por um corretor.**

> Status: em uso diário em produção (uso próprio) e em preparação para abertura do código.
> Este repositório é a casa pública do projeto. O código vem para cá em etapas, já limpo de
> dados de clientes.

---

## Por que existe

O Brasil tem centenas de milhares de corretores de imóveis, e a maioria trabalha sozinha:
atende os leads pelo WhatsApp, anota em caderno ou planilha e perde vendas por falta de
follow-up. Os CRMs imobiliários do mercado são caros, pensados para imobiliárias grandes e
fechados.

Este projeto nasceu do dia a dia de um corretor e arquiteto-urbanista no litoral de Santa
Catarina (Balneário Camboriú, Itapema e Porto Belo). A pergunta foi simples: **como seria um CRM
feito por quem atende lead todo dia?**

## O que já funciona (versão em produção)

- **WhatsApp integrado:** as conversas entram sozinhas no CRM, com contatos e etiquetas.
- **Registro automático de ligações:** pelo WhatsApp e pelo celular, com duração, sem gravar
  a conversa. O CRM identifica o lead e pede revisão quando não tem certeza.
- **Painel do dia:** quem respondeu, quem está esperando, ligações recentes e alertas.
- **Ficha do lead:** histórico de mensagens, ligações e anotações num só lugar.
- **Vigia de saúde:** se o celular ou o WhatsApp param de mandar sinal, o CRM avisa no
  Telegram.
- **Qualidade:** mais de 1.400 testes automatizados.

## O que está sendo construído

- **Funil de vendas completo:** Kanban arrastável e um desenho de funil de verdade, com a
  quantidade de leads em cada etapa (Novo → Respondeu → Qualificado → Ligação → Videochamada →
  Proposta → Reserva → Cliente).
- **Nutrição inteligente:** listas separadas para quem vai comprar no futuro e para quem está
  pronto agora, com data prevista de compra e aviso na hora certa de retomar.
- **Tudo metrificado:** conversão entre etapas, tempo em cada etapa, taxa de reativação. Com
  isso o CRM aprende com os dados reais de cada corretor.
- **IA como assistente:** sugere o próximo passo de cada lead, e o corretor confirma.
- **Relatório pós-ligação:** depois de cada ligação, o CRM pede um resumo (por texto ou
  áudio) e guarda na ficha.
- **Envio no fuso certo:** para o comprador que mora no exterior, mensagem no horário dele,
  não às 22 h.

## A visão

Ser a ferramenta padrão do corretor independente no Brasil e na América Latina: **gratuita,
aberta e fácil de instalar**, para quem não é programador. Software livre para um mercado que
movimenta centenas de bilhões de reais por ano e, em boa parte, ainda trabalha no caderno.

## Roteiro de abertura

1. **Agora:** apresentação do projeto e roteiro público (este repositório).
2. **Separar o núcleo:** tirar do código tudo o que é específico do meu negócio e qualquer
   dado de cliente.
3. **Publicar o código** com licença aberta, documentação em português e instalação guiada.
4. **Comunidade:** guias para corretores, exemplos e caminho para contribuir.

## Tecnologia

Next.js · React · TypeScript · Supabase (PostgreSQL) · Docker · Evolution API (WhatsApp).

## Como foi feito

O CRM foi construído por um corretor que não é programador de formação, em parceria com o
[Claude Code](https://claude.com/claude-code). É a tese do projeto: com a IA certa, um
profissional de qualquer área cria as ferramentas de que precisa, e pode devolvê-las abertas
para quem trabalha como ele.

---

**Autor:** Luigi Bono Bolfer, arquiteto-urbanista e corretor de imóveis no litoral de SC.
Quer acompanhar ou ajudar? Abra uma *issue* neste repositório.
