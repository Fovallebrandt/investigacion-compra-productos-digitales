# Guia operacional — Hotmart por “7 dias para explorar sua respiração”
**Versão:** 0.1.0  
**Situação:** pesquisa aplicada; você não cria uma conta nem publica o curso.  
**Atualizado:** 22/10/2026 18:11 CLST  
**Escopo:** produtor com residência/operação no Chile; compradores iniciais no Chile, México e Espanha.
## Resultado
**Fato observado:** A Hotmart permite cadastrar um curso online com pagamento único, hospedá-lo no Hotmart Club, organizar módulos, criar oferta com link de pagamento e agendar a liberação do conteúdo de acordo com a data de compra. Também oferece períodos de garantia de 7, 15, 21 ou 30 dias para cursos online. [Curso online: criação e configuração](https://help.hotmart.com/es/article/360037537591/curso-online-todo-lo-que-necesitas-saber-para-crear-y-configurar-tu-curso) · [Módulos no Hotmart Club](https://help.hotmart.com/es/article/360000645592/como-criar-e-gerenciar-modulos-no-hotmart-club) · [Lançamento agendado](https://help.hotmart.com/es/article/como-configurar-o-prazo-de-liberacao-e-duracao-de-conteudos-na-area-de-gestao-do-curso-/213467588)
**Inferência operacional:** a arquitetura mais simples para esta primeira versão é: pouso Respiro y Conecto → link de pagamento de uma oferta Hotmart → Hotmart Club para o curso. Não requer a criação de contas, pagamentos ou seu próprio LMS antes de vender.
**Limite:** Nenhuma fonte avaliada pode ter certeza de qual moeda ou mídia aparecerá em uma finalização de compra específica antes de concluir o registro e testar com uma conta/produto real.
## Configuração de produto recomendada
| Elemento | Configuração proposta | Situação da decisão |
|---|---|---|
| Tipo | Curso on-line | Compatível com a estrutura do programa. |
| Coleção | Pagamento único | Acordado para a primeira versão. |
| Entrega | Clube Hotmart / Área de Membros | Proposta operacional; não está configurado. |
| Estrutura | Módulos Dia 0 ao Dia 7 | Compatível com software existente. |
| Desembarque | Página própria do Respiro y Conexão que direciona para o link de pagamento | Acordado como direção de implementação. |
| Preço e moeda | Uma oferta inicial | **Decisão pendente.** Não publique sem defini-las. |
| Garantia | 7, 15, 21 ou 30 dias | **Decisão pendente.** A Hotmart oferece essas alternativas de cursos online. |
| Tempo de acesso | Definir expressamente no produto | **Decisão pendente.** Não presuma acesso vitalício ou limitado. |
## Passos para torná-lo funcional
### 1. Crie e valide a conta do produtor
1. Crie a conta Hotmart como produtor.
2. Preencha os documentos solicitados pelo fluxo de verificação.
3. Aguarde a aprovação documental antes de cadastrar a conta bancária de aposentadoria. A Hotmart indica que a análise pode levar até cinco dias úteis. [Documentos da conta](https://help.hotmart.com/es/article/216440217/-que-documentos-debo-enviar-para-crear-mi-cuenta-en-hotmart-)
4. Cadastre a conta bancária de saque e revise a moeda disponível para receber pagamentos. [Conta bancária e transferências](https://help.hotmart.com/es/article/24183626321165/-como-configurar-mi-cuenta-bancaria-para-la-transferencia-automatica-de-comisiones-)
5. Confirmar com um contador ou consultor fiscal chileno a emissão de documentos fiscais, declaração de rendimentos e impostos aplicáveis. A Hotmart não substitui aquela avaliação local.
**Pendência que requer Fernando:** informações de identidade, informações fiscais e conta bancária. Esta etapa não pode ser legitimamente concluída ou simulada sem eles.
### 2. Cadastre o curso e ofereça
1. Crie um produto do tipo **curso online**.
2. Selecione **pagamento único**.
3. Defina preço, moeda e garantia. O guia da Hotmart indica que você pode optar por pagamento único e que a garantia pode ser de 7, 15, 21 ou 30 dias. [Curso online: criação e configuração](https://help.hotmart.com/es/article/360037537591/curso-online-todo-lo-que-necesitas-saber-para-crear-y-configurar-tu-curso)
4. Crie uma **oferta**: ali é definido o preço base e a Hotmart gera o link de pagamento. [Crie uma oferta de pagamento único](https://help.hotmart.com/es/article/215827788/como-criar-uma-oferta-para-o-meu-produto-de-pagamento-unico)
5. Mantenha uma única oferta inicial. Não crie descontos, pacotes, afiliados ou assinaturas antes de validar a compra básica.
### 3. Prepare a Área de Membros
Crie estes módulos:
| Módulo | Conteúdo mínimo que deve existir antes da publicação |
|---|---|
| Dia 0 — Boas vindas e preparação | Vídeo de boas-vindas, segurança e como usar o notebook. |
| Dia 1 — Observação | Prática guiada e acesso ao Caderno Digital. |
| Dias 2–6 | Vídeo educativo e/ou prática correspondente; link para caderno. |
| Dia 7 — Integração | Prática, encerramento e reflexão final. |
| Suporte | Email ou formulário de contato e uma breve explicação de acesso. |
**Fato observado:** O Hotmart Club permite agrupar aulas, vídeos, quizzes e recursos em módulos. Também permite que o conteúdo seja lançado em uma data específica ou alguns dias após a compra. [Módulos](https://help.hotmart.com/es/article/360000645592/como-criar-e-gerenciar-modulos-no-hotmart-club) · [Lançamento agendado](https://help.hotmart.com/es/article/como-configurar-o-prazo-de-liberacao-e-duracao-de-conteudos-na-area-de-gestao-do-curso-/213467588)
**Decisão pendente:** A pesquisa não determina se o Dia 0 e o Dia 1 devem aparecer na compra. Duas opções coerentes são:
- Dia 0 e Dia 1 disponíveis imediatamente; O dia 2 é lançado um dia após a compra e assim por diante.
- Apenas o Dia 0 disponível imediatamente; O dia 1 é lançado no dia seguinte.
**Inferência:** A primeira opção reduz a espera e permite que as boas-vindas levem diretamente ao primeiro treino. Deve ser confirmado antes de definir datas.
### 4. Conecte o patamar ao caixa
1. Conclua uma pequena página de vendas no Respiro y Conexão.
2. Inclua um único botão principal: “Iniciar 7 dias” ou equivalente.
3. Vincule esse botão ao link de pagamento gerado pela oferta da Hotmart.
4. Antes do botão, mostre: o que inclui, formato, lançamento diário, preço final, moeda, garantia, tempo de acesso, avisos de segurança e canal de suporte.
5. Não prometa resultados clínicos nem use o checkout para ocultar condições de pagamento ou reembolso.
### 5. Revise os pagamentos por país sem assumir disponibilidade
**Fato observado:** Hotmart documenta cartões de crédito e débito para América Latina e Europa, PayPal e mais de 30 métodos para compradores em mais de 180 países. Também documenta cotas para produtos vendidos a compradores no Chile e no México. [Métodos de venda](https://help.hotmart.com/es/article/25588460435085/-que-metodos-de-pago-estan-disponibles-y-como-puedo-habilitarlos-para-mi-producto-) · [Cotas no Chile e México](https://help.hotmart.com/es/article/4404509205005/-como-funciona-el-pago-en-cuotas-para-quienes-venden-en-chile-peru-mexico-colombia-y-brasil-) · [Métodos de compra](https://help.hotmart.com/es/article/25648853025037/-cuales-son-los-metodos-de-pago-disponibles-para-comprar-en-hotmart-)
| Mercado | Métodos mencionados na documentação do Hotmart | O que falta verificar |
|---|---|---|
| Chile | Cartão; MACH, Sencillito e Servipag aparecem na documentação de compra/reembolso. | Quais aparecerão nesta oferta, em que moeda e em que condições. |
| México | Cartão; Mercado Pago, SPEI e OXXO aparecem na documentação de compra/reembolso. | Quais aparecerão nesta oferta e se o fluxo é adequado para um curso de baixo custo. |
| Espanha | Cartão; Klarna está documentada para compradores na Espanha em produtos digitais de pagamento único, com elegibilidade e limites locais. | Quais opções específicas uma pessoa verá dependendo da quantidade e do perfil; Eles não são garantidos para todos os compradores. |
**Aviso:** Não anuncie publicamente MACH, OXXO, Klarna ou qualquer outro método até verificar se o checkout real mostra isso para aquele país. A disponibilidade depende do país, quantidade, produto, conta e avaliação do fornecedor. [Klarna no Hotmart](https://help.hotmart.com/es/article/38465293543309/como-vender-con-klarna-en-hotmart)
### 6. Operação, acesso e suporte
- Após uma compra aprovada, a pessoa faz login com o e-mail utilizado na compra no ambiente Hotmart. [Acesso do comprador](https://help.hotmart.com/es-LA/article/215827338/como-accedo-al-producto-que-compre-en-hotmart)
- Definir um e-mail de suporte da Respiro y Conecta para: problemas de acesso, dúvidas do curso e dúvidas sobre o conteúdo.
- Explique claramente o período de garantia escolhido. Uma solicitação de devolução ou estorno não deve ser atendida com promessas informais: revise o status da transação e as regras da Hotmart.
- Revise vendas, pagamentos e retiradas do painel antes de comunicar um novo grupo ou investimento publicitário.
## Testes obrigatórios antes de abrir vendas
| Teste | Resultado a verificar |
|---|---|
| Link do pouso | Isso leva à oferta certa, com o produto, preço e moeda certos. |
| Check-out do Chile | Métodos visíveis, preço, moeda e condições reais. |
| Check-out do México | Métodos visíveis, preço, moeda e condições reais. |
| Check-out da Espanha | Métodos visíveis, preço, moeda e condições reais. |
| Compra experimental aprovada | E-mail de confirmação e acesso sem intervenção manual. |
| Área de membros | São mostrados apenas os módulos que correspondem ao dia de acesso. |
| Lançamento Diário | O dia seguinte abre no horário configurado para a compra. |
| Móvel | Landing, checkout, vídeos, áudios, links e Caderno Digital funcionam no celular. |
| Suporte e devoluções | Correio de suporte visível; garantia e processo comunicados claramente. |
| Aposentadoria | Conta bancária e moeda de saque confirmadas no painel. |
## Ordem de serviço
### Sem dados pessoais ou bancários
1. Conclua o conteúdo e os arquivos de cada dia.
2. Escolha qual das duas regras de liberação usar.
3. Prepare a página de vendas e o texto de suporte/garantia.
4. Definir uma proposta de preço, sem publicá-la ainda.
### Com dados pessoais, fiscais e bancários
5. Crie/verifique a conta do produtor e registre a retirada.
6. Crie curso, módulos, oferta, preço e garantia.
7. Insira o link de pagamento na landing page.
### Antes do lançamento
8. Faça os testes da tabela anterior, de preferência com pessoas reais localizadas no Chile, México e Espanha.
9. Corrija os atritos observados.
10. Venda aberta somente quando comprovado compra, acesso, entrega e suporte.
## Decisões que permanecem em aberto
- Preço e moeda base.
- Período de garantia.
- Período de acesso ao curso.
- Disponibilidade imediata no dia 1 ou lançamento no dia seguinte.
- Texto final de termos, privacidade, suporte e impostos; requer revisão local quando aplicável.
- Métodos de pagamento realmente disponíveis para esta conta e oferta.
## Fontes oficiais consultadas
- [Hotmart: curso online, criação e configuração](https://help.hotmart.com/es/article/360037537591/curso-online-todo-lo-que-necesitas-saber-para-crear-y-configurar-tu-curso)
- [Hotmart: documentos da conta](https://help.hotmart.com/es/article/216440217/-que-documentos-debo-enviar-para-crear-mi-cuenta-en-hotmart-)
- [Hotmart: oferta de pagamento único](https://help.hotmart.com/es/article/215827788/como-criar-uma-oferta-para-o-meu-produto-de-pagamento-unico)
- [Hotmart: Módulos da Área de Membros](https://help.hotmart.com/es/article/360000645592/como-criar-e-gerenciar-modulos-no-hotmart-club)
- [Hotmart: lançamento agendado](https://help.hotmart.com/es/article/como-configurar-o-prazo-de-liberacao-e-duracao-de-conteudos-na-area-de-gestao-do-curso-/213467588)
- [Hotmart: formas de pagamento](https://help.hotmart.com/es/article/25648853025037/-cuales-son-los-metodos-de-pago-disponibles-para-comprar-en-hotmart-)
- [Hotmart: Klarna](https://help.hotmart.com/es/article/38465293543309/como-vender-con-klarna-en-hotmart)