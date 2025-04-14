# Análise de Requisitos

## Introdução

Este documento descreve os requisitos funcionais e não funcionais do **Sistema de Gerenciamento de Estacionamento**, visando atender às necessidades de administração eficiente de um estacionamento.

## Objetivos

- Automatizar o processo de controle de vagas disponíveis e ocupadas.
- Gerenciar o fluxo de entrada e saída de veículos.
- Manter um registro detalhado dos clientes.
- Fornecer histórico completo das atividades de estacionamento.

O **Sistema de Gerenciamento** permitirá:

- Cadastro e atualização de informações sobre as vagas de estacionamento.
- Registro das entradas e saídas de veículos, associando-os aos clientes cadastrados.
- Consulta e manutenção dos dados dos clientes.
- Geração de relatórios históricos sobre a utilização do estacionamento.

## Principais Usuários

- **Administradores**: Responsáveis pelo gerenciamento do sistema.
- **Clientes/Motoristas**: Usuários que utilizarão os serviços do estacionamento e do sistema.

O sistema será composto por módulos interligados que permitirão a gestão completa do estacionamento, desde o cadastro de vagas até a análise do histórico de uso. O sistema será interligado com base no banco de dados, conectando desde a coleta de dados do sensor até a aplicação **Desktop**.

## Requisitos Funcionais

### Cadastro de Clientes
- O sistema deve permitir o cadastro de clientes, armazenando informações pessoais e de contato.

### Cadastro de Vagas
- O sistema deve permitir que o administrador cadastre novas vagas, especificando características como localização e tipo.

### Atualização de Vagas
- O sistema deve possibilitar a atualização das informações das vagas existentes.

### Registro de Entrada de Veículo
- O sistema deve registrar a entrada de um veículo, associando-o a uma vaga disponível e, se aplicável, a um cliente cadastrado.

### Registro de Saída de Veículo
- O sistema deve registrar a saída de um veículo, liberando a vaga correspondente e calculando o tempo de permanência.

### Consulta de Clientes
- O sistema deve possibilitar a consulta e atualização dos dados dos clientes cadastrados.

### Histórico de Estacionamentos
- O sistema deve manter um registro histórico de todas as entradas e saídas de veículos, incluindo detalhes como horário, cliente associado e vaga utilizada.

### Geração de Relatórios
- O sistema deve gerar relatórios sobre a ocupação das vagas, frequência de clientes e outros dados relevantes.

## Requisitos Não Funcionais

### Usabilidade
- O sistema deve possuir uma interface intuitiva e de fácil navegação para os usuários.

### Desempenho
- O sistema deve processar as operações de registro de entrada e saída de veículos em tempo real.

### Segurança
- O sistema deve garantir a proteção dos dados dos clientes e das operações realizadas, implementando controles de acesso adequados.

### Disponibilidade
- O sistema deve estar disponível para operação sempre que necessário.

### Escalabilidade
- O sistema deve ser capaz de suportar um aumento no número de vagas e clientes sem degradação de desempenho.
