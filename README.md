# Performance (JMeter)


### Tópicos 

 [Descrição do projeto](#descrição-do-projeto)

- [Ferramentas utilizadas](#ferramentas-utilizadas)

- [Pré requisitos / Instruções](#pré-requisitos)


## Descrição do projeto

Projeto desenvolvido para testes automatizados de performance, utilizando a ferramenta JMeter.

O maior objetivo é acompanhamento da performance em produção, além de demais ambientes para garantir maior qualidade nas entregas realizadas! 

### Ajustes e melhorias

O projeto ainda está em desenvolvimento e as próximas atualizações serão voltadas nas seguintes tarefas:

- [x] Criação do projeto base
- [x] Criação dos cenários principais baseados na Squad Sysops
- [x] Criação dos arquivos JMX (ambiente produção)
- [ ] Criação de uma pipeline
- [ ] ...

## Ferramentas utilizadas

### Sistemas Operacionais

  ![Mac os](https://img.shields.io/badge/mac%20os-%23525252.svg?style=flat&logo=macos&logoColor=white>)
  ![Linux](https://img.shields.io/badge/-Linux%20-%23525252.svg?style=flat&logo=linux&logoColor=white&>)
  ![Windows](https://img.shields.io/badge/-Windows%20-%23525252.svg?style=flat&logo=Windows&>)

### Ferramentas de desenvolvimento

  ![JMeter](https://img.shields.io/badge/-jmeter-333333?style=flat&logo=apachejmeter)
  ![Git](https://img.shields.io/badge/-Git-333333?style=flat&logo=git)
  ![Bitbucket](https://img.shields.io/badge/-Bitbucket-333333?style=flat&logo=bitbucket)

## Pré requisitos / Instruções

Antes de começar, será necessário realizar o download da ferramenta JMeter!

O JMeter é um Java puro, este aplicativo deve ser executado corretamente em qualquer sistema que tenha compatibilidade Java implementação

Link Download JMeter : https://jmeter.apache.org/

Link Extensão Blazemeter : https://chromewebstore.google.com/detail/blazemeter-the-continuous/mbopgmdnpcbohhpnfglgohlbhfongabi?hl=en


* Iniciar o JMeter para realizar a leituras dos arquivos JMX
* Instalação da extensão do Blazemeter para realizar a captura de request URL's para acompanhamento da performance de cada cenário!
* Instalar a versão mais recente do JAVA SE Development Kit

Passo à passo da execução : https://petz.atlassian.net/wiki/spaces/SYSOPS/pages/3136618497/Performance+Jmeter+-+Pipeline


## Como instalar? 
 

Versão mais atual é a 5.6.3, segue o passo a passo da instalação;

Por ser uma ferramenta desenvolvida em Java, requer uma JVM (Java Virtual Machine) 8 ou superior, siga o passo a passo para instalação do Java em sua máquina;

Link : https://www.java.com/pt-BR/download/help/windows_manual_download.html#download

Faça o Download do Jmeter;

Apache JMeter - Download Apache JMeter 

Extraia o arquivo "apache-jmeter-5.6.3.zip" para uma pasta desejada.

Executando o JMeter
Para executar o JMeter, devemos ir no diretório $Local de instalação do JMeter\bin\. Para executar no Windows devemos utilizar o arquivo jmeter.bat, para executar no Linux ou Mac devemos utilizar o arquivo jmeter.

Ao acessar o diretório, navegue até a aba "Exibir" e marque a opção "Extensões de nomes de arquivos". Após selecionar o arquivo que corresponde ao seu SO o JMeter será executado e está pronto para uso.
