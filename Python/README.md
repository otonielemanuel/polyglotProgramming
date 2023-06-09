<h1 align="center">Python</h1>

<img src="./assets/python.jpg" alt="Python" />

<p>Python é uma linguagem de programação interpretada, de alto nível e de propósito geral criada por Guido van Rossum em 1991. </p>
<p>O nome "Python" foi dado em homenagem ao grupo de comédia britânico Monty Python, do qual o criador era um grande fã.</p>
<p>Ao longo dos anos, Python ganhou popularidade por ser fácil de usar, ter uma sintaxe clara e intuitiva, e uma grande quantidade de recursos prontos para uso.</p>
<p>Python é uma linguagem poderosa que pode ser usada para uma ampla variedade de tarefas, desde a criação de pequenos scripts até a implementação de grandes projetos complexos. Com sua grande quantidade de bibliotecas prontas para uso, Python facilita o desenvolvimento de projetos.</p>

## 📚 Índice

+ [Para que serve?](#🧰-para-que-serve)
+ [Instalação](#💻-instalação)
+ [VSCode](#🔧-vscode)
+ [Online Code](#🌐-online-code)
+ [Guia de estudo](#📖-guia-de-estudo)
+ [Ferramentas e bibliotecas](#🛠️-ferramentas-e-bibliotecas)
+ [Projetos  populares](#🚀-projetos-populares)
+ [Comunidade](#👥-comunidade)
+ [Créditos](#👨🏽‍💼-créditos)

## 🧰 Para que serve?

<p>Python é uma linguagem de programação amplamente utilizada em várias áreas, incluindo:</p>

+ <strong>Desenvolvimento web:</strong> muitos frameworks web, como o Django e o Flask, são escritos em Python, tornando-o uma escolha popular para o desenvolvimento de aplicativos web.

+ <strong>Ciência de dados:</strong> Python é uma das principais linguagens usadas em ciência de dados, graças às suas bibliotecas que permitem aos cientistas de dados trabalhar facilmente com grandes conjuntos de dados, realizar análises estatísticas e criar visualizações.

+ <strong>Aprendizado de máquina:</strong> Python é uma das principais linguagens usadas em aprendizado de máquina e inteligência artificial, com bibliotecas que permitem aos desenvolvedores criar redes neurais e modelos de aprendizado de máquina.

+ <strong>Automação de tarefas:</strong> Python é frequentemente usado para automatizar tarefas repetitivas, como coletar informações da web, enviar e-mails, manipular arquivos e muito mais.

+ <strong>Segurança cibernética:</strong> Python é frequentemente usado em segurança cibernética para criar scripts de detecção e análise de ameaças.

+ <strong>Jogos:</strong> Python é usado para criar jogos e engines de jogos, como o Pygame.

> Em resumo, Python é uma linguagem de programação versátil que pode ser usada em uma ampla variedade de aplicativos e projetos.

## 💻 Instalação

<p>Python pode ser facilmente instalado em diferentes sistemas operacionais, incluindo Windows, macOS e Linux. Existem várias maneiras de instalar Python, como a instalação direta do site oficial do Python ou por meio de gerenciadores de pacotes, como o pip.</p>

### Windows

Para instalar o Python no Windows, siga os seguintes passos:

1. Acesse o site oficial do Python <a href="https://www.python.org/downloads/" target="_blank">aqui</a> e baixe a versão mais recente do Python. Certifique-se de baixar a versão que corresponde ao seu sistema operacional e à sua arquitetura (32 bits ou 64 bits);

2. Após o download, execute o arquivo .exe que foi baixado e siga as instruções do instalador.

3. Na tela "Customize Python", certifique-se de marcar a opção "Add Python to environment variables". Isso permitirá que você execute o Python a partir do prompt de comando.

4. Conclua a instalação seguindo as demais instruções do instalador.

5. Para testar se a instalação foi bem-sucedida, abra o prompt de comando do Windows e digite:

```
python --version
```
Se tudo estiver correto, o prompt deve exibir a versão do Python instalada.

<p>Pronto, agora você tem o Python instalado no seu Windows!</p>

### Linux

Para instalar o Python no Linux, siga os seguintes passos:

1. Abra o terminal e atualize os pacotes do sistema com o comando:

```
sudo apt-get update
```

2. Instale o Python digitando o comando:

```
sudo apt-get install python3
```

3. Verifique se a instalação foi bem-sucedida digitando o comando:

```
python3 --version
```

Se tudo estiver correto, o terminal deve exibir a versão do Python instalada.

Pronto, agora você tem o Python instalado no seu Linux! Note que, dependendo da distribuição que você está usando, os comandos e a forma de instalar o Python podem variar. Por exemplo, em algumas distribuições você pode precisar usar yum em vez de 'apt-get'.

### macOS

Para instalar o Python no Mac, siga os seguintes passos:

1. Acesse o site oficial do Python <a href="https://www.python.org/downloads/" target="_blank">aqui</a>  e baixe a versão mais recente do Python. Certifique-se de baixar a versão que corresponde ao seu sistema operacional e à sua arquitetura (32 bits ou 64 bits).

2. Após o download, abra o arquivo .dmg que foi baixado e execute o instalador.

3. Siga as instruções do instalador e conclua a instalação.

4. Abra o terminal e verifique se a instalação foi bem-sucedida digitando o comando:

```
python3 --version
```

Se tudo estiver correto, o terminal deve exibir a versão do Python instalada.

## 🔧 VSCode

Tendo o Python instalado na sua máquina, para programar em Python no Visual Studio Code (VSCode), siga os seguintes passos:

1. Instale a extensão "Python" no VSCode. Para fazer isso, abra o VSCode e clique no ícone de extensões no lado esquerdo da tela <strong>(ou pressione Ctrl+Shift+X)</strong>. Na barra de busca que aparecer, digite "Python" e pressione Enter. Na lista de extensões que aparecer, clique em "Python" e clique no botão "Install".

> Você pode instalar as extenções que achar que o auxiliarão no desenvolvimento em Python.

2. Crie um novo arquivo Python no VSCode. Para fazer isso, clique em "File" no menu superior, selecione "New File" e salve o arquivo com a extensão '<strong>.py</strong>'. Por exemplo, você pode salvar o arquivo como "index.py".

3. Escreva o seu código Python no arquivo criado. Por exemplo:

```python
print('Hello world!')
```
> Este código irá imprimir um "Hello, world!".

4. Salve o arquivo pressionando <strong>Ctrl+S</strong>.

5. Abra o terminal integrado do VSCode pressionando Ctrl+Ç e no terminal integrado, navegue até o diretório onde você salvou o arquivo Python digitando o comando:

```bash
cd caminho/do/diretorio
```

6. Execute o arquivo Python digitando o comando:

```python
python index.py
```

> Repare que o 'index' é o nome do nosso arquivo Python, você deverá substitui-lo pelo nome do seu arquivo.

Se tudo estiver correto, o VSCode deve exibir a mensagem "Hello, world!" no terminal.

> Agora você sabe como programar em Python no VSCode! É possível configurar várias opções de configuração e depuração no VSCode para tornar o seu processo de desenvolvimento ainda mais fácil e produtivo.

## 🌐 Online code

<p>Existem várias plataformas online que permitem programar em Python sem precisar instalar um ambiente de desenvolvimento integrado (IDE) localmente. Algumas opções populares são:</p>

+ <a href="https://www.pythonanywhere.com/" target="_blank">PythonAnywhere</a> 

+ <a href="https://repl.it/languages/python3" target="_blank">Repl.it</a>
+ <a href="https://colab.research.google.com/" target="_blank">Google Colab</a>
+ <a href="https://jupyter.org/try" target="_blank">Jupyter Notebook</a>

Cada uma dessas plataformas tem suas próprias vantagens e desvantagens, então é importante escolher a que melhor se adequa às suas necessidades. Algumas delas têm recursos avançados para programação científica, enquanto outras são mais adequadas para iniciantes ou para programação web.


## 📖 Guia de estudo

Existem muitos recursos disponíveis para quem deseja aprender Python, incluindo a <a href="https://docs.python.org/pt-br/3/tutorial/index.html" target="_blank">documentação oficial</a>, tutoriais em vídeo e cursos on-line.

Índice de estudo da linguagem Python:

<strong>Conceitos básicos de programação</strong>
+ Variáveis e tipos de dados
+ Operadores e expressões
+ Estruturas de controle de fluxo (if/else, while, for)
+ Funções
+ Listas, tuplas e dicionários
+ Módulos e pacotes

<strong>Sintaxe básica do Python</strong>
+	Indentação
+	Comentários
+	Funções built-in (print, input, range, etc.)
+	Strings
+	Manipulação de arquivos

<strong>Programação orientada a objetos</strong>
+	Classes e objetos
+	Herança e polimorfismo
+	Encapsulamento e abstração

<strong>Bibliotecas e ferramentas úteis</strong>
+	NumPy (manipulação de arrays numéricos)
+	Pandas (análise de dados)
+	Matplotlib (visualização de dados)
+	Flask (desenvolvimento web)
+	Pygame (desenvolvimento de jogos)

<strong>Projetos práticos</strong>
+	Cálculo de IMC
+	Jogo da forca
+	Calculadora
+	Análise de dados de vendas
+	Aplicativo web simples

É importante lembrar que este é apenas um guia e não a ordem exata para se estudar Python, é importante praticar com exercícios e projetos práticos para realmente aprimorar suas habilidades em Python.

## 🛠️  Ferramentas e bibliotecas

Python possui uma ampla variedade de bibliotecas e frameworks que facilitam o desenvolvimento em diversas áreas. Confira uma pequena lista das mesmas separadas por áreas.

<strong>Ciência de Dados e Aprendizado de Máquina</strong>
+	NumPy: para cálculos numéricos eficientes.
+	Pandas: para manipulação e análise de dados.
+	Matplotlib: para visualização de dados.
+	Scikit-learn: para aprendizado de máquina e mineração de dados.
+	TensorFlow: para desenvolvimento de modelos de aprendizado de máquina.
+	PyTorch: outra biblioteca para desenvolvimento de modelos de aprendizado de máquina.
+	Keras: para construção e treinamento de redes neurais.

<strong>Desenvolvimento Web</strong>
+	Django: para desenvolvimento de aplicações web completas.
+	Flask: para construção de aplicações web simples e leves.
+	BeautifulSoup: para fazer web scraping (coleta de dados de websites).
+	Requests: para fazer requisições HTTP em aplicações web.

<strong>Desenvolvimento de jogos</strong>
+	Pygame: Uma biblioteca popular para criar jogos em Python, que oferece suporte a gráficos 2D e áudio, além de entrada do usuário.
+	PyOpenGL: Uma biblioteca que oferece suporte ao OpenGL em Python, o que permite criar gráficos 3D para jogos.
+	Panda3D: Uma biblioteca de código aberto que fornece ferramentas para criar jogos em 3D e outras aplicações interativas.
+	Arcade: Uma biblioteca relativamente nova, voltada para a criação de jogos em 2D, mas que tem ganhado popularidade por sua facilidade de uso e recursos.
+	Pyglet: Uma biblioteca para jogos em 2D e 3D, que oferece suporte a gráficos, som e entrada do usuário.

É importante lembrar que existem muitas outras bibliotecas e ferramentas disponíveis para o Python, e essas são só algumas das várias.

## 🚀 Projetos populares

Alguns dos projetos populares criados em Python incluem:

+ <a href="https://open.spotify.com/?" target="_blank">Spotify</a> - um serviço de streaming de música muito popular que utiliza Python para gerenciar seus recursos.
+ <a href="https://www.youtube.com/" target="_blank">YouTube</a> - A plataforma de compartilhamento de vídeos mais popular do mundo utiliza Python em grande escala para gerenciamento de tráfego, armazenamento e processamento de dados.
+ <a href="https://www.netflix.com/ao/" target="_blank">Netflix</a> - um dos serviços de streaming de vídeo mais populares do mundo, que usa Python para gerenciar suas operações e dados.
+ <a href="https://www.instagram.com/" target="_blank">Instagram</a> - um aplicativo de compartilhamento de fotos e vídeo muito popular que foi construído com Python e Django.
+ <a href="https://www.dropbox.com/" target="_blank">Dropbox</a> - um serviço de armazenamento em nuvem que usa Python para gerenciar suas operações.

## 👥 Comunidade

A comunidade Python é reconhecida como uma das maiores e mais ativas comunidades de desenvolvimento de software do mundo, composta por milhões de desenvolvedores, usuários e entusiastas de Python em todo o mundo. Ela é inclusiva, colaborativa e encoraja a contribuição de desenvolvedores para a linguagem, documentação e projetos de código aberto relacionados. Há muitos recursos disponíveis para a comunidade, incluindo bibliotecas e frameworks de código aberto, além de tutoriais, cursos e documentação útil. A comunidade Python é ativa no desenvolvimento de novas tecnologias, como inteligência artificial, aprendizado de máquina e análise de dados.

Aqui estão alguns links para algumas das principais comunidades Python no Github:

+ https://github.com/python - Organização oficial do Python no Github, com vários projetos relacionados à linguagem e à sua comunidade.

+ https://github.com/psf - Python Software Foundation, organização sem fins lucrativos responsável pelo desenvolvimento e promoção da linguagem Python.

+ https://github.com/pyenv - Pyenv, gerenciador de versões do Python que permite instalar e alternar entre diferentes versões da linguagem.

Aqui estão alguns perfis e hashtags que você pode seguir para se manter atualizado sobre as novidades da comunidade Python no Twitter:

+ <a href="https://twitter.com/ThePSF" target="_blank">@ThePSF</a> - conta oficial da Python Software Foundation, que promove o desenvolvimento e a adoção da linguagem Python em todo o mundo.
+ <a href="https://twitter.com/pybites" target="_blank">@pybites</a> - perfil que compartilha dicas e desafios relacionados à linguagem Python, além de promover a comunidade de desenvolvedores em torno da linguagem.
+ <a href="https://twitter.com/realpython" target="_blank">RealPython</a> - perfil que compartilha tutoriais, dicas e recursos para desenvolvedores Python, além de promover a comunidade Python em geral.

## 👨🏽‍💼 Créditos

<p>Este repositório foi inicialmente criado pelo Otoniel Emanuel, um estudante de programação e apaixonado por tecnologia. Obviamente com o crescimento da repositório, outras pessoas também daram as suas contribuições.</p>

### 📱 Redes sociais

+ <a href="https://www.linkedin.com/in/otoniel-emanuel-b80727261/" target="_blank">LinkedIn</a>
+ <a href="https://www.instagram.com/eusouootis_" target="_blank">Instagram</a>


