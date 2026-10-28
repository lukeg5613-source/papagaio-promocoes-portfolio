# Evidências e limites — Papagaio Promoções / PromoBot

Revisão estática em **28/10/2026**, sem autenticar plataformas, abrir bancos, enviar mensagens, executar testes ou alterar serviços.

| Afirmação | Evidência privada consultada | Limite |
|---|---|---|
| Recepção, normalização e deduplicação | Pipeline, monitor Telegram, extratores e matcher | Implementação existente; operação atual não foi revalidada |
| Origem e atraso entre ocorrências | Camada de atribuição e persistência | Não se publica identificação de fontes reais |
| Histórico e regras de qualidade | Persistência, histórico de preços e políticas | Não constitui previsão de preço ou garantia de oferta |
| Central de revisão | Interface e serviço de cópias original/revisada | Preparar ou copiar conteúdo não comprova envio |
| 604 testes, incluindo 44 novas regressões offline | Relatório interno de qualidade de dados | Resultado histórico; documento sem data explícita; não reexecutado nesta revisão |
| Shadow de distribuição | Documentação e serviço de registro de decisões | Simulação de decisão não equivale a ativação do canal |
| Integrações opcionais | Módulos e dependências identificados | Não comprova disponibilidade, autorização de conta ou estabilidade operacional |

O README original representa um MVP anterior e não descreve toda a evolução. Este estudo cruzou sua descrição com módulos e relatórios posteriores. A presença de uma opção de configuração não é prova de ativação; arquivos de segredos e sessões não foram abertos.

## Exemplo técnico sanitizado

O marco de qualidade trata valores monetários agrupados, condições de cupom confundidas com preço e identidade insuficiente de produto. O portfólio resume as classes de problema sem reproduzir mensagens, IDs ou URLs reais das fontes.

## Imagens

As duas capturas selecionadas vêm de cenários identificados como fixture. A imagem desktop contém itens marcados TESTE e fonte de teste. Contadores, preços e cadência visíveis pertencem ao cenário de demonstração. A imagem mobile mostra o painel desse cenário. Não há exposição de sessão, cookie, token, destinatário real ou link de afiliado.

## Não medido

Não se apresentam usuários, audiência, volume atual de publicações, economia de tempo, conversão, receita, comissões ou taxa de deduplicação. Também não se afirma funcionamento completo dos canais externos em produção.
