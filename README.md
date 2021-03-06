<h1 align="center">
 :robot: I.A para Algoritmos Genéticos
</h1><br/>

## Atividade da Matéria de I.A. um Algoritmo Genético de timetabling educacional <span style="font-size: 32px"> :date:</span>

<br/>

- Ter configurado no <i>host</i> em que será executado o codigo o:<br/>
  - <strong>Python 3.6 + </strong> <br/>
  - <strong>Virtualenv </strong> <br/>

<span>:page_facing_up:</span> <strong>Links:</strong> <br/>
https://docs.python.org/pt-br/3/library/venv.html

## :factory: Criando Virtualenv: <br/>

### <strong>Ambiente Linux:</strong><br/>

Para criar o ambiente execute: <br/>
<strong>python3 -m venv myvenv</strong><br/><br/>
Note que uma pasta chamada <i>myvenv</i> foi criada,
então execute a partir da raiz do projeto o comando para ativa-la:<br/>
<strong>source myvenv/bin/activate</strong><br/>
Para executar entre na pasta
<strong>app</strong> e execute o comando:<br/>
<strong>uvicorn api:app --reload</strong><br/>

### <strong>Ambiente Windows:</strong><br/>

Para criar o ambiente execute: <br/>
<strong>py -m venv myvenv</strong><br/><br/>
Note que uma pasta chamada <i>myvenv</i> foi criada,
então execute a partir da raiz do projeto o comando para ativa-la:<br/>
<strong>. myvenv/Script/activate</strong><br/>

<!-- Para executar entre na pasta
<strong>app</strong> e execute o comando:<br/>
<strong>uvicorn main:app --reload</strong><br/> -->

<!-- ## :hammer: Instalação das Dependências:<br/>

Note que um arquivo <i>requeriments.txt</i> está na raiz do projeto, o mesmo contem todas as dependências do projeto, para instalar execute: <br/>
<strong>pip install -r requirements.txt</strong><br/> -->