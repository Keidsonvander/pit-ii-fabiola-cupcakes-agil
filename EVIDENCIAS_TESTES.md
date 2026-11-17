# Evidências dos Testes e Correções — PIT II

**Aluna:** Fabiola Saviato  
**RGM:** 33636702  
**Projeto:** Sistema web para vendas online de cupcakes gourmet  
**Data dos testes:** 17/11/2026

## Participantes
- Camila Fernanda Ribeiro
- Diego Henrique Martins
- Bruna Letícia Carvalho
- Gustavo Alexandre Lima
- Mariana Lopes de Almeida

## 1. Mensagem após inclusão no carrinho
**Problema identificado:** a confirmação apresentada após adicionar um produto possuía pouco destaque visual.

**Correção aplicada:** foram criadas mensagens específicas de sucesso e erro, com maior contraste e texto mais claro.

**Evidência:** classes `msg ok` e `msg erro` e função `mensagem()` adicionadas ao arquivo `index.html`.

## 2. Controles do carrinho em telas menores
**Problema identificado:** os botões de aumentar, diminuir e remover produtos ficavam próximos em telas reduzidas.

**Correção aplicada:** os controles passaram a ter maior espaçamento, área de toque ampliada e quebra de linha quando necessário.

**Evidência:** ajustes nas classes `acoes` e `mini` no media query para telas de até 600 pixels.

## 3. Orientação e validação do telefone
**Problema identificado:** o campo de telefone não apresentava exemplo ou indicação do formato esperado.

**Correção aplicada:** foi incluído exemplo com DDD, orientação de preenchimento e validação de 10 ou 11 dígitos.

**Evidência:** placeholder, texto auxiliar e validação `telefoneLimpo` no formulário.

## 4. Destaque da etapa atual
**Problema identificado:** a etapa atual do acompanhamento precisava ser mais evidente.

**Correção aplicada:** a situação “Pedido recebido” recebeu maior destaque visual e a indicação “atual”.

**Evidência:** atualização das classes `etapa ativa atual` no bloco de acompanhamento.

## 5. Resumo final do pedido
**Problema identificado:** a confirmação final apresentava poucas informações sobre a compra.

**Correção aplicada:** foi incluído um resumo com produtos, quantidades, valores, cliente, forma de pagamento, modalidade de entrega e status atual.

**Evidência:** novo bloco `confirmacao` criado na finalização do pedido.

## Nova verificação
Após as correções, foram revistos:
- catálogo;
- inclusão de produtos;
- alteração de quantidades;
- remoção de itens;
- cálculo do total;
- mensagens de sucesso e erro;
- validação de dados;
- pagamento;
- entrega;
- acompanhamento;
- resumo final;
- responsividade.

O fluxo principal apresentou funcionamento satisfatório após os ajustes.

## Funcionalidades previstas para evolução futura
- cadastro e autenticação de clientes;
- cupons e promoções;
- confirmação de telefone;
- pagamento real;
- rastreamento em tempo real;
- histórico de pedidos;
- área administrativa;
- testes em maior variedade de dispositivos e navegadores.
