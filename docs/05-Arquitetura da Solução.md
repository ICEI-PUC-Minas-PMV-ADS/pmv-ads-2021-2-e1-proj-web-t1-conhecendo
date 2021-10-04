# Arquitetura da Solução

Definição de como o software é estruturado em termos dos componentes que fazem parte da solução e do ambiente de hospedagem da aplicação.


## Diagrama de componentes

Diagrama que permite a modelagem física de um sistema, através da visão dos seus componentes e relacionamentos entre os mesmos.

Exemplo: 

Os componentes que fazem parte da solução são apresentados na figura arquitetura de solução.
![imagem2](https://user-images.githubusercontent.com/80737152/135862447-3217c95d-6a43-46e5-b733-24a5f9228fc2.jpg)


A solução implementada conta com os seguintes módulos:
- **Navegador** - Interface básica do sistema  
  - **Páginas Web** - Conjunto de arquivos HTML, CSS, JavaScript e imagens que implementam as funcionalidades do sistema.
   - **Local Storage** - armazenamento mantido no Navegador, onde são implementados bancos de dados baseados em JSON. São eles: 
     - **Canais** - seções de notícias apresentadas 
     - **Comentários** - registro de opiniões dos usuários sobre as notícias
     - **Preferidas** - lista de notícias mantidas para leitura e acesso posterior
 - **News API** - plataforma que permite o acesso às notícias exibidas no site.
 - **Hospedagem** - local na Internet onde as páginas são mantidas e acessadas pelo navegador. 

> **Links Úteis**:
>
> - [Whimsical](https://whimsical.com/)




## Tecnologias Utilizadas

As tecnologias utilizadas, para resolver o problema, ou seja implementar a solução, são descritas abaixo.

![usuariosistema](https://user-images.githubusercontent.com/80737152/135863033-3a2769e5-b699-4527-bde6-3deb0a1a15bc.png)


Implementação de solução:

    • Linguagens: Páginas web; html css Java script;
    • Frameworks: Board;
    • Serviços web: HTPP;
    • IDEs de desenvolvimento: Visual Studio Code;
    • Ferramentas: Mapeamento do processo, organização de informações, busca de soluções, análise de dados.
    

## Hospedagem

O site utiliza a plataforma do Github como ambiente de hospedagem.O site e mantido no ambiente da URL:
https://github.com

A publicação do site no Github é feita por meio de uma submissão do projeto (push) via git para o repositório remoto que se encontra no endereço: https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2021-2-e1-proj-web-t1-conhecendo
