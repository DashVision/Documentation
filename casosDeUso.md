## 01 - Cadastrar Cliente
Ator principal: Administrador

- Descrição: Permite ao administrador registrar um novo cliente no sistema.

- Pré-condição: O administrador está autenticado no sistema.

Fluxo principal:

- O administrador acessa a tela de cadastro de cliente.

- Preenche os dados do cliente (nome, CPF, contato, etc).

- Confirma o cadastro.

- O sistema salva os dados e exibe uma mensagem de sucesso.

Pós-condição: Cliente cadastrado no banco de dados.

## 02 – Registrar Entrada de Veículo
Ator principal: Administrador

- Descrição: Associa um veículo a uma vaga disponível e inicia a contagem de tempo.

- Pré-condição: O cliente (ou veículo) já está cadastrado no sistema.

Fluxo principal:

- O administrador acessa a tela de registro de entrada.

- Seleciona o veículo e a vaga disponível.

- Confirma o registro.

- O sistema marca a vaga como ocupada e inicia o tempo.

Pós-condição: Vaga ocupada e entrada registrada.

## 03 – Registrar Saída de Veículo
Ator principal: Administrador

- Descrição: Finaliza a permanência do veículo e libera a vaga.

- Pré-condição: O veículo está registrado como “ocupando uma vaga”.

Fluxo principal:

- O administrador acessa a tela de saída.

- Seleciona o veículo/vaga.

- Confirma a saída.

- O sistema calcula o tempo, libera a vaga e armazena no histórico.

Pós-condição: Vaga liberada e histórico atualizado.
## 04 – Consultar Histórico
Ator principal: Administrador

- Descrição: Permite consultar entradas e saídas passadas.

- Pré-condição: Deve haver registros anteriores.

Fluxo principal:

- O administrador acessa a área de relatórios.

- Seleciona os filtros desejados (data, cliente, vaga, etc).

- O sistema exibe os dados solicitados.
