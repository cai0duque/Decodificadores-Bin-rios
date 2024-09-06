# Circuitos Digitais

Na atual versão, o projeto é uma simulação de **decodificadores** e **multiplexadores** em Java, permitindo que o usuário interaja com diferentes tipos de circuitos digitais. O objetivo é proporcionar uma ferramenta para estudar e simular o comportamento desses componentes, que são muito utilizados em sistemas digitais, como controle de memória, multiplexação de sinais e seleção de linhas.

O projeto inclui os seguintes tipos de decodificadores e multiplexadores:

# Decodificadores:
- **2x4**: Converte 2 bits de entrada em uma única saída entre 4 possíveis.
- **3x8**: Converte 3 bits de entrada em uma única saída entre 8 possíveis.
- **4x16**: Converte 4 bits de entrada em uma única saída entre 16 possíveis.
- **5x32**: Converte 5 bits de entrada em uma única saída entre 32 possíveis.
- **6x64**: Converte 6 bits de entrada em uma única saída entre 64 possíveis.
- **7x128**: Converte 7 bits de entrada em uma única saída entre 128 possíveis.
- **8x256**: Converte 8 bits de entrada em uma única saída entre 256 possíveis.
- **9x512**: Converte 9 bits de entrada em uma única saída entre 512 possíveis.

# Multiplexadores:
- **4x1**: Recebe 4 entradas e utiliza 2 bits de controle para selecionar qual entrada será encaminhada para a saída.
- **8x1**: Recebe 8 entradas e utiliza 3 bits de controle para selecionar qual entrada será encaminhada para a saída.

# Como Funciona

- Decodificadores:
O decodificador recebe um número de entradas binárias e ativa uma saída específica com base na combinação de bits de entrada. Cada decodificador tem um número específico de entradas e saídas.

- Multiplexadores:
O multiplexador seleciona uma de várias entradas com base em um conjunto de bits de controle (seletores) e direciona essa entrada para a saída. Isso é útil para reduzir a quantidade de conexões necessárias em sistemas digitais.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Instalação

- 1> Clone a pasta do código este repositório:
   ```bash
   git config core.sparseCheckout true
   echo "src/" >> .git/info/sparse-checkout
   git clone https://github.com/cai0duque/Circuitos-logicos.git

- 2> Compile os arquivos java
javac -d bin src/decodificador/*.java


