Esteira Didática Automatizada

Este repositório contém todos os arquivos e documentação relacionados ao projeto da uma esteira didática automatizada. O objetivo deste projeto é desenvolver uma esteira didatica automatizada utilizando sensores, ESP32, motor de passo e servo motor.

📜 Descrição do Projeto

A esteira didática automatizada é um sistema que simula o funcionamento de uma esteira industrial com controle automatizado, presente na indústria. O sistema é capaz de:

Detectar objetos por meio de sensores.

Controlar a movimentação da esteira com um motor de passo acionado por um Driver TB6600.

Separar objetos por meio de um servo motor.

Exibir informações no display LCD 2004.

⚙️ Tecnologias Utilizadas:

ESP32: Microcontrolador usado no sistema.

C: Linguagem de programação usada no firmware do ESP32.

Sensores: Leitura de presença de objetos, detecção de metais e leitura e validação da velocidade do motor de passo.

Motor de Passo NEMA23: Controle de movimentação da esteira.

Driver TB6600: Acionar o motor de passo

Servo Motor: Controle de posicionamento dos objetos ao final da esteira.

Optoacopladores: Isolação dos sinais entre o esp32 e os sensores e o servo motor.

Display LCD: Exibição de informações do sistema.


📂 Estrutura do Repositório

├── code/                # Código-fonte em C/C++ para o ESP32
├── docs/                # Documentação do projeto
├── images/              # Imagens do projeto e dos componentes
├── videos/              # Vídeos demonstrativos do funcionamento da esteira
├── report/              # Relatório completo do TCC
└── README.md            # Arquivo de descrição do projeto

🚀 Como Executar o Projeto

1. Clone o repositório:

git clone https://github.com/seu-usuario/esteira-didatica.git

2. Abra o código do ESP32 (localizado na pasta code/) no seu editor de código preferido (ex: VSCode, Arduino IDE, PlatformIO).

3. Carregue o código no ESP32 utilizando o cabo USB.

4. Certifique-se de que todos os componentes eletrônicos estão conectados conforme o esquema de montagem.

5. Execute o sistema e acompanhe a exibição de dados no display LCD e o funcionamento da esteira.

6. Ajuste a frequencia de clock para alterar a velocidade da esteira.

7. Insira os blocos para testar a esteira

📚 Documentação

Você pode encontrar a documentação detalhada do projeto, incluindo o relatório final do TCC, na pasta docs/.

🖼️ Imagens e Vídeos

Na pasta images/ e videos/, você encontrará imagens e vídeos que mostram o desenvolvimento e o funcionamento da esteira didática automatizada.

📄 Relatório do TCC

O relatório completo do TCC está disponível na pasta report/.

🛠️ Contribuições

Se você deseja contribuir com o projeto, sinta-se à vontade para abrir issues ou enviar pull requests. Toda ajuda é bem-vinda!


---

📞 Contato

Caso tenha dúvidas ou sugestões sobre o projeto, entre em contato:

Nome: Allison Prado 

E-mail: allison_prado@hotmail.com 

LinkedIn: 
