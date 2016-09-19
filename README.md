# Projetos em Python
### Pequenos projetos e testes simples em linguagem Python.

### Descrição:

###### Os programas apresentados neste repositório são apenas projetos simples e testes escritos na linguagem Python.
###### Alguns destes programas são utilitários e scripts que podem ser utilizados no dia-a-dia para realização de algumas funções.
###### Os programas aqui contidos foram desenvolvidos pensando na plataforma Linux e UNIX em geral, podendo não funcionar na plataforma Windows!

### Programas:

#### Heavy-R Downloader

##### Descrição:

###### Este é um simples programa que possui a função de baixar vídeos do site Heavy-R.
###### O programa cria uma pasta no mesmo diretório que está sendo executado e nele cria os diretórios para os vídeos que irá baixar.
###### Ao executar o programa, basta inserir a URL da página do vídeo desejado.
###### Os vídeos serão baixados em formato '.mp4', com o nome do vídeo original (sem espaços).

###### Aqui estão os possíveis argumentos que poderão ser inseridos na hora de executar o programa:


    Uso: ./Heavy-R Downloader.py [Argumento] [URL / ID]
    ---------------------------------------------------
    
    Argumentos:
    -----------
    '-h' ou '--help':    Mostra a tela de ajuda
    '-u' ou '--url':     Utiliza a URL inserida como argumento para o programa
    '-i' ou '--id':     Utiliza a ID inserida como argumento para o programa
    

##### Requisitos:
- Python 2.x
- BeautifulSoup

###### É necessário possuir o BeautifulSoup para que o programa possa funcionar.
###### Caso não tenha o BeautifulSoup, utilize o comando abaixo:

    sudo pip install beautifulsoup4

##### Download:

###### Você poderá baixar o programa com os comandos abaixo:

    git clone https://github.com/Wolfterro/Projetos-em-Python.git
    cd "Projetos-em-Python/Heavy-R Downloader"
    chmod +x "HeavyRDownloader.py"
    ./HeavyRDownloader.py

#### GUROchan Image Downloader

##### Descrição:

###### Este programa possui a função de baixar imagens de um tópico escolhido do GUROchan.
###### Ao executar o programa, ele irá criar, no mesmo diretório que está sendo executado, uma pasta chamada 'GUROchan'.
###### Ao executá-lo, basta inserir a URL do tópico desejado.
###### Nesta pasta, as imagens baixadas serão organizadas por pastas de acordo com a board onde o tópico reside.

##### Requisitos:
- Python 2.x
- BeautifulSoup

###### É necessário possuir o BeautifulSoup para que o programa possa funcionar.
###### Caso não tenha o BeautifulSoup, utilize o comando abaixo:

    sudo pip install beautifulsoup4

##### Download:

###### Você poderá baixar o programa com os comandos abaixo:

    git clone https://github.com/Wolfterro/Projetos-em-Python.git
    cd "Projetos-em-Python/GUROchan\ Image\ Downloader"
    chmod +x "GUROchan-Image-Downloader.py"
    ./GUROchan-Image-Downloader.py

#### z0r Downloader

##### Descrição:

###### Este é um simples programa que possui a função de baixar animações do site z0r.de.
###### O programa cria uma pasta no mesmo diretório que está sendo executado e nela serão armazenadas as animações.
###### Ao executar o programa, basta inserir a ID da animação desejada.
###### As animações serão baixadas em formato '.swf', com a ID como nome do arquivo.
###### É possível também inserir múltiplas ID's no programa atráves de argumentos pela linha de comando.

###### Aqui estão os possíveis argumentos que poderão ser inseridos na hora de executar o programa:


    Uso: ./z0r-downloader.py [Argumento] [ID] ...
    ---------------------------------------------
    
    Argumentos:
    -----------
    '-h' ou '--help':    Mostra a tela de ajuda
    '-i' ou '--input':   Baixa através de ID's inseridas na linha de comando
    '-r' ou '--range':   Baixa animações entre um valor mínimo e um valor máximo
    '-a' ou '--all':     Baixa TODAS as animações do z0r.de
    
    Exemplo de uso para argumento '-r' ou '--range':
    ------------------------------------------------
    Uso: z0r-downloader.py [-r/--range] [min] [max]

##### Requisitos:
- Python 2.x

##### Download:

###### Você poderá baixar o programa com os comandos abaixo:

    git clone https://github.com/Wolfterro/Projetos-em-Python.git
    cd "Projetos-em-Python/z0r Downloader"
    chmod +x "z0r-downloader.py"
    ./z0r-downloader.py
