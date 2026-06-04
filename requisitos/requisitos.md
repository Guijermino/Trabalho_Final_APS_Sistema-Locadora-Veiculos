# Sistema de Locadora de Veículos

## Descrição do Sistema

O Sistema de Locação de Veículos tem como objetivo auxiliar uma empresa locadora no controle de clientes, veículos e locações. O sistema permitirá o cadastro e a consulta de clientes, a verificação da disponibilidade dos veículos, o registro de locações e devoluções, além do processamento de pagamentos.

Também serão disponibilizadas funcionalidades administrativas, como o cadastro de funcionários e a emissão de relatórios de locações e veículos. Dessa forma, o sistema busca tornar o processo de locação mais organizado, seguro e eficiente, facilitando o gerenciamento das informações da empresa.

---

# Requisitos Funcionais (RF)

## RF01 - Cadastrar Cliente

O sistema deve permitir o cadastro de clientes.

## RF02 - Consultar Cliente

O sistema deve permitir consultar clientes cadastrados.

## RF03 - Cadastrar Veículo

O sistema deve permitir cadastrar veículos.

## RF04 - Consultar Veículo

O sistema deve permitir consultar veículos cadastrados.

## RF05 - Verificar Disponibilidade

O sistema deve permitir verificar a disponibilidade de veículos.

## RF6 - Registrar Locação

O sistema deve permitir registrar uma locação.

## RF7 - Registrar Devolução

O sistema deve permitir registrar a devolução de veículos.

## RF8 - Calcular Valor da Locação

O sistema deve calcular automaticamente o valor total da locação.

## RF9 - Registrar Pagamento

O sistema deve permitir registrar pagamentos.

## RF10 - Emitir Relatório de Veículos e Locações

O sistema deve gerar relatórios dos veículos cadastradose das locações realizadas.

## RF11 - Cadastrar Funcionário

O sistema deve permitir cadastrar funcionários.

## RF12 - Realizar Login

O sistema deve permitir autenticação por login e senha.

---

# Requisitos Não Funcionais (RNF)

## RNF01 - Interface

O sistema deve possuir interface intuitiva e de fácil utilização.

## RNF02 - Desempenho

As consultas devem ser respondidas em até 3 segundos.

## RNF03 - Segurança

O acesso deve ser realizado por login e senha.

## RNF04 - Persistência

Os dados devem ser armazenados em banco de dados.

## RNF05 - Manutenibilidade

O código deve seguir boas práticas de orientação a objetos.

---

# Regras de Negócio (RN)

## RN01: Um veículo só poderá ser locado se estiver disponível.

## RN02: O valor da locação deve ser calculado com base na quantidade de dias locados e na diária do veículo.

