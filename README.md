
# Sistema_de_Compras_Publicas-React

Sistema_de_Compras_Publicas-React é uma aplicação React desenvolvida em Typescript, utilizando MongoDB com Replication Set e Axios para comunicação com APIs REST usadas como microsserviços. O objetivo principal do Sistema de Compras Públicas é facilitar a geração, armazenamento e gestão da documentação para processos de contratações, também conhecidos como Processos Licitatórios, visando uma melhor gestão dos mesmos, por meio de um ambiente digital onde é possível ter acesso a todos os processos da organização e retirando a necessidade de uso de documentos impressos, agilidade no trâmite do processo pelo envio dos documentos para quem é responsável por cada parte para confecção ou assinatura. Além disso, oferece recursos para monitorar e visualizar o andamento desses processos em diferentes etapas.

## Funcionalidades

+ **Geração e Armazenamento de Documentos:** Permite aos usuários gerar, criar e armazenar documentos essenciais relacionados aos processos de contratação. Esses documentos podem incluir editais, propostas e outros.

+ **Gerenciamento de Processos:** A aplicação oferece uma interface amigável para gerenciamento de processos de contratação. Usuários podem criar novos processos, atribuir responsabilidades e definir marcos.

+ **Acompanhamento de Processos:** Fornece uma visão geral do status atual de cada processo de contratação. Os usuários podem identificar facilmente em que etapa o processo se encontra e acessar os documentos relevantes.

+ **Replication Set:** É construído usando MongoDB com Replication Set, garantindo redundância de dados, alta disponibilidade e tolerância a falhas.

+ **Chamadas Assíncronas:** A aplicação utiliza chamadas assíncronas para proporcionar interações fluídas e atualizações em tempo real aos usuários, melhorando a experiência sem necessidade de recarregar a página.

+ **Comunicação com APIs REST:** A aplicação possui uma estrutura baseada em microsserviços e é responsável, através do **Axios**, pela comunicação com as APIs, garantindo maior desempenho.

+ **Design Responsivo:** O aplicativo foi projetado para se adaptar a diferentes tamanhos de tela, utilizando **Bootstrap** para facilitar essa adaptação.

<hr>

+ **GERENCIAMENTO DE PROCESSOS**
  
<div style="display: inline">
<img src="https://lh3.googleusercontent.com/pw/ADCreHe7c6GlpbMj8dSbzXexGSfy1KhD96YQH26wQAOq8at3wl7ngeyfdbwcmKwKGjQxsZWh-AJ-3nCWXqCK6x3MJe1kqqOblSwq08QaETth3Wi2a7QEu6ppf6-BI8hUebYUtE_El1mkyltPrsPc-yOJBA=w1702-h924-s-no?authuser=1" width="400px" />
<img src="https://lh3.googleusercontent.com/pw/ADCreHcbTV9GkjNUZFm7ZCkotBDlnJWNFP4Qm3mFHB6QMpn7OdhiSAaTLJ8GlFXjeTKmpzXmbEPUsjpKqb7W10R4qW3VM-j9AEtECa9tyccf73hW4wz47Xx7yshgGIB_qhNJkbq0LP5t0fR7dJRr1pRj3w=w1707-h924-s-no?authuser=1" width="400px" />  
</div>

<div style="display: inline">
<img src="https://lh3.googleusercontent.com/pw/ADCreHeZA1IMgydCyVP3RvRG4s3LOWKsazQeIT_7Dz1ev9M25Jg0RG9C-q_eNkdv8VLu8Vr3Lu7UUMExwLfGY0SeDVXEom08ffNksHl5c0OX8C_qt92JJ6l3yD6Owm3WN1zx3w8Q51MlG8TJU4hyPyPqMA=w1698-h924-s-no?authuser=1" width="400px" />
<br>

+ **ENVIO DE MENSAGENS E PROCESSOS**

<div style="display: inline">
<img src="https://lh3.googleusercontent.com/pw/ADCreHfYKvMvfAckHGkypTbqI9D2fOUAoAt3YG8K8BCUrJnaPorC1ZT2MxkbcQgmHKdx9bDI4GlYl6xLSq7pW2Gu4Ves2SocXLm7_yY73-L-kJu79Wa_XlThEl9P9QX5SIxijXyVhUlJX-Cdckyf_AHlEg=w1698-h924-s-no?authuser=1" width="400px" />
<img src="https://lh3.googleusercontent.com/pw/ADCreHdm-_p7H00ot5VWAIB3qvqWSCewRNb4m3To9wmxA1wSl3modPKtgToaPvjGYrnsK89ISRh4NhsKgYIzL5mCBI8gIEySa9c9gD-QHHYul2-d6GNmj_fQOzRoRjTZj95Kbnj5hy5Nq8NdSAKt1EZzbw=w1702-h924-s-no?authuser=1" width="400px" />  
</div>
<br>
 
## Requisitos

+ Node.js 16+
+ MongoDB 5.0.22+

## Como Instalar

### APIs Necessárias
+ Para rodar corretamente a versão React do SisCoP, é necessário baixar as APIs responsáveis pela comunicação com o banco de dados e upload de arquivos. Siga os passos para cada API:

1. API de Comunicação com Banco de Dados: https://github.com/Jorge-Luiz-11/Sistemas_de_Compras_Publicas_API
2. API de Comunicação de Upload de Arquivos.

### Baixar o SisCoP React
1. Clone o projeto do GitHub. Troque "myproject" pelo nome do seu projeto ou baixe usando o botão "Download Zip":
```bash
git clone https://github.com/Jorge-Luiz-11/Sistemas_de_Compras_Publicas-REACT.git ./myproject
```

### Baixar e Descompactar
1. Baixe o repositório.
2. Descompacte no diretório desejado.

### Instalar Dependências
1. Abra um terminal na pasta do repositório.
2. Execute o comando para instalar as dependências do projeto:
```bash
npm install
```

### Preparar o Ambiente
1. Crie um arquivo chamado ***.env*** e insira as variáveis de ambiente:
```sh
REACT_APP_SISCOP_API=[Insira aqui a URL da API responsável pelo processamento do banco de dados] Ex: http://127.0.0.1:3999
REACT_APP_SISCOP_API_UPLOAD=[Insira aqui a URL da API responsável pelo Upload] Ex: http://127.0.0.1:3998
```    

## Como Rodar
1. Para rodar a aplicação utilize:
```bash
npm start
```
+ Após isso, acesse http://[seu HOST selecionado]:[sua PORTA selecionada].
+ Para login, utilize: login: "ADM" / senha: "123456".
