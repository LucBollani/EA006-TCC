# EA006 - Trabalho de fim de curso
## Análise e simulação de tráfego de pacotes para jogos online

Este repositório compila os documentos necessários para a compreensão do projeto de fim de curso para a disciplina EA006 da Universidade Estadual de Campinas.

![alt text](https://github.com/LucBollani/EA006-TCC/blob/main/TFC/img1.PNG)

## Resumo

Este projeto de TCC consistiu em realizar a captura do tráfego de pacotes comunicados entre o cliente e o servidor de dois jogos multiplayer online, analisando sua distribuição em relação ao tamanho e tempo entre partida. Para isso, foi desenvolido um modelo para a re-criação de novos pacotes estatisticamente equivalentes aos originais, permitindo a simulação de jogadores e o teste da capacidade e jogabilidade de um servidor.

O jogo utilizado para a analise e desenvolvimento da ferramenta foi o Valorant da Riot games studio, e o jogo utilizado para o teste de capacidade do servidor foi um jogo personalizado, desenvolvido previamente e disponibilizado em [Unity Networking Learning](https://github.com/LucBollani/unity_network_learning). 

## Estrutura de arquivos
<pre>

.
├── <b>TFC/</b>
│   ├── <b>client_packets/</b>
│   │   │   Diretório contendo capturas de pacotes pequenas, utilizadas
│   │   │   durante desenvolvimento do projeto
│   │   │
│   │   ├── <b>client_emptyudp.pcap</b>
│   │   │   Captura de pacote UDP sem dados, utilizado como base para a
│   │   │   criação de novos pacotes
│   │   │
│   │   ├── <b>client_player1.pcap</b>
│   │   ├── <b>client_player2.pcap</b>
│   │   ├── <b>client_player3.pcap</b>
│   │   │   Captura de comportamento de jogador, usadas como teste
│   │   │   para reproduzir exatamente os movimentos de um jogador num bot
│   │   │
│   │   ├── <b>client_welcomereceived.pcap</b>
│   │   │   Captura de pacote de handshake entre cliente e servidor,
│   │   │   usado para autenticar um usuário no servidor do jogo
│   │   │
│   │   └── <b>readme.txt</b>
│   │       Arquivo de descrição do conteúdo do diretório
│   │
│   ├── <b>FPSGAME_client.pcap</b>
│   │   Captura de tráfego do jogo personalizado, utilizada para
│   │   análise, simulação e avaliação final da ferramenta produzida no 
│   │   projeto
│   │
│   ├── <b>NB 1 - VALORANT.ipynb</b>
│   │   Notebook Jupyter contendo todos os códigos e resultados da
│   │   análise do primeiro jogo tratado: Valorant
│   │ 
│   ├── <b>NB 2 - CUSTOM_GAME.ipynb</b>
│   │   Notebook Jupyter contendo todos os códigos e resultados da
│   │   análise do segundo jogo tratado: Jogo Personalizado
│   │
│   ├── <b>Relatorio.docx</b>
│   │   Relatório final apresentado para a disciplina
│   │
│   ├── <b>Valorant_TDM_client_UDP.pcap</b>
│   │   Captura de tráfego do jogo Valorant numa partida online,
│   │   utilizada para análise e simulação da ferramenta produzida no
│   │   projeto
│   │
│   ├── <b>img1.PNG</b>
│   │   Logotipo da faculdade
│   │
│   └── <b>requirements.txt</b>
│       Lista de bibliotecas python e suas versões utilizadas no projeto
│ 
└── <b>Readme.md</b>
    Descrição inicial do projeto e conteúdo do repositório

</pre>