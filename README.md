![](https://img.shields.io/badge/cucumber-v.0.0.1-yellow.svg)
![](https://img.shields.io/badge/selenium-v.3.141.59-green.svg)
# Exercicio- Site: Torne-se um Programador 
<br>
<br>

## Exercício passado pelo professor Danilo, durante a academia Accenture.<br> 
<b>Objetivo:</b> O objetivo do exercício era testar o [site torne-se um programador](https://www.torneseumprogramador.com.br/) e buscar algumas informações.
<br>
<br>
## Caso de Teste :red_circle: <br>
Entrar no site torneseumprogramador e pesquisar algumas informaçoes<br>
<b>Cenario I:</b> Pesquisando tdd<br>
	  Quando eu acesso o site do tornese um programador <br>
	  E digito no campo busca "tdd"<br>
	  E clico no botao pesquisar<br>
	  Entao devo acessar a pagina com resultados de busca.<br>
<br>   
<b>Cenario II:</b> Pesquisando bdd<br>
	  Quando eu acesso o site do tornese um programador <br>
	  E digito no campo busca "bdd"<br>
	  E clico no botao pesquisar<br>
	  Entao devo acessar a pagina com resultados de busca<br>
<br>  
<br>
<br>
## Tecnologias utilizadas :heart_eyes: <br>
 :white_check_mark: <b>Java</b><br>
> Linguagem de programação para desenvolvimento da aplicação.<br>
 
 :white_check_mark: <b>Selenium</b><br>
> Framework responsável por fazer a integração do código java com a linguagem Gherkin(Cucumber) abrindo o browser fazendo o teste de comportamento.<br>
 
 :white_check_mark: <b>Cucumber</b><br>
> Framework responsável por traduzir uma linguagem humana em código Java.<br>

:white_check_mark: <b>Maven</b><br>
> Gerenciador de dependências para o Java.<br>

<br>
<br>
<br>

## Como utilizar :computer:<br>

- Instalar o [Java](https://www.java.com/pt-BR/download/ie_manual.jsp?locale=pt_BR)
- Instalar [JDK](https://www.oracle.com/br/java/technologies/javase/javase-jdk8-downloads.html)
- Verificar se o JAVA_HOME está configurado em seu computador.
- Clone do projeto.<br>
`` git clone https://github.com/sarahhraamos/Exercicio_testeautomatizado.git ``
- Entrando na pasta do projeto<br>
`` cd Exercicio_testeautomatizado ``
- Fazer o download do [Chrome Webdriver](https://chromedriver.chromium.org/downloads) e colocar o arquivo descompactado dentro da pasta driver na raiz do projeto:<br>
<b>Exemplo:</b><br>
``cd driver``<br>
``curl https://chromedriver.storage.googleapis.com/89.0.4389.23/chromedriver_linux64.zip``<br>
``unzip chromedriver_linux64.zip``<br>
``rm -rf chromedriver_linux64.zip``<br>
``cd ../driver``<br>
- Limpando e validando maven Unix<br>
``./mvnw clean``<br>
- Limpando e validando maven Windows<br>
``mvnw.cmd clean``<br>
- Executando teste no Unix<br>
``./test.sh``<br>
- Executando teste no Windows<br>
``test.bat``<br>

<br>
<br>
<br>
