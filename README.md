# EcommerceDB - Modelagem de Banco de Dados

Objetivo:
Refinar o modelo apresentado abaixo acrescentando os seguintes pontos:

- **Cliente PJ e PF** – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
- **Pagamento** – Pode ter cadastrado mais de uma forma de pagamento;
- **Entrega** – Possui status e código de rastreio.
- 
# Modelo original:

![br_modelo_ecommerce](https://github.com/user-attachments/assets/b118ec0f-b51b-4ffe-8ea6-766e25447d7f)



Projeto consiste na modelagem e implementação de um banco de dados para um sistema de e-commerce, utilizando MySQL, inserindo os pontos de melhoria supracitado no desafio da DIO.

## 📌 Estrutura do Banco de Dados
- **Clientes (PJ e PF)** com um tipo específico.
- **Pedidos** relacionados a clientes.
- **Pagamentos** associados aos pedidos (múltiplos métodos por pedido).
- **Entregas** com status e código de rastreamento.
- **Produtos** vinculados a fornecedores, estoques e vendedores terceiros.

  # Modelo após melhorias solicitadas:

  ![modelo_eer_ecommerce](https://github.com/user-attachments/assets/87b1110a-3d68-40b1-8c48-7b927c2884bf)


## 🚀 Como Utilizar
1. Execute o script `ecommerce_model.sql` em seu MySQL Workbench para criar as tabelas.
2. Utilize **MySQL Workbench** para visualizar a modelagem (diagrama EER disponível no repositório).

## 📂 Arquivos no Repositório
- `ecommerce_model.sql` → Script SQL do banco de dados.
- `modelo_eer.png` → Diagrama da modelagem no Workbench.

