# Documentação do Projeto — PIT II

## Identificação
**Aluna:** Fabiola Saviato  
**RGM:** 33636702  
**Projeto:** Sistema web para vendas online de cupcakes gourmet

## 1. Continuidade da PIT I
A PIT II dá continuidade ao projeto desenvolvido anteriormente para uma loja de cupcakes gourmet.

A proposta mantém o foco na organização das vendas online e na construção de um fluxo simples para catálogo, carrinho, pedido, pagamento, entrega e acompanhamento.

## 2. Objetivo
Transformar o planejamento da PIT I em uma solução funcional e testável, mantendo coerência entre requisitos, funcionalidades e experiência do usuário.

## 3. Principais atores
- Cliente;
- Administrador da loja;
- Entregador.

## 4. Fluxo principal
1. acesso à aplicação;
2. visualização do catálogo;
3. inclusão dos produtos no carrinho;
4. conferência do pedido;
5. preenchimento dos dados do cliente;
6. escolha da forma de pagamento;
7. escolha da modalidade de entrega;
8. finalização;
9. confirmação;
10. acompanhamento simplificado do pedido.

## 5. Requisitos Funcionais
**RF01:** Exibir catálogo de cupcakes.  
**RF02:** Exibir nome, descrição e preço dos produtos.  
**RF03:** Permitir adicionar produtos ao carrinho.  
**RF04:** Permitir alterar quantidades e remover itens.  
**RF05:** Calcular o valor total automaticamente.  
**RF06:** Permitir informar os dados do cliente.  
**RF07:** Permitir selecionar forma de pagamento.  
**RF08:** Permitir selecionar modalidade de entrega.  
**RF09:** Permitir finalizar o pedido.  
**RF10:** Exibir confirmação e acompanhamento simplificado.

## 6. Requisitos Não Funcionais
- interface clara e simples;
- layout responsivo;
- boa legibilidade;
- navegação intuitiva;
- validação dos campos obrigatórios;
- retorno visual após ações;
- organização do código e documentação.

## 7. Histórias de Usuário
- Como cliente, quero visualizar os cupcakes disponíveis para escolher o que comprar.
- Como cliente, quero adicionar e ajustar produtos no carrinho para montar meu pedido.
- Como cliente, quero informar meus dados para concluir a compra.
- Como cliente, quero escolher a forma de pagamento e entrega.
- Como cliente, quero visualizar a confirmação e o status inicial do pedido.

## 8. Regras de Negócio
- não permitir finalizar pedido sem produtos;
- exigir os dados obrigatórios;
- permitir somente as formas de pagamento disponíveis;
- exigir uma modalidade de entrega;
- gerar um número de identificação para o pedido.

## 9. Backlog Priorizado
### Alta prioridade
- catálogo;
- carrinho;
- dados do cliente;
- pedido;
- pagamento;
- entrega.

### Média prioridade
- confirmação;
- acompanhamento;
- responsividade.

### Evoluções futuras
- login e cadastro;
- pagamento real;
- rastreamento em tempo real;
- histórico de pedidos;
- painel administrativo.

## 10. Tecnologias
- Front-end demonstrativo: HTML, CSS e JavaScript;
- Estrutura de aplicação: React/Vite como referência do projeto;
- Back-end: Python com Flask;
- Banco de dados: SQLite;
- Hospedagem da demonstração: GitHub Pages.

## 11. Controle de versão
O código-fonte, a documentação e as correções realizadas após os testes ficam registrados neste repositório GitHub.
