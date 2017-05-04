# Projeto: Reinforcement Learning
## Treinando um taxi a dirigir

Neste projeto você aplicara técnicas de aprendizagem por reforço para um agente auto-condutor em um mundo simplicicado, auxiliando-o a chegar de maneira efetiva até seus destinos em um tempo atribuído.

### Instalação

Esse projeto utiliza **Python 2.7** junto com [pygame](https://www.pygame.org/wiki/GettingStarted).

Requisitos de software.

[Python 2.7]()
[NumPy]()
[PyGame]()

Recomendações

Você pode instalar diretamente o [Anaconda]() que contem a maior parte das biblitecas importantes.

Para instalar o [PyGame]() de forma a pode utilizar a visualização da tela do PyGame installe da seguinte forma.

Mac: 

```conda install ­c https://conda.anaconda.org/quasiben pygame```

Windows e Linux:

```conda install -c https://conda.anaconda.org/tlatorre pygame

### Codigo

O codigo que será usado nessa atividade está na pasta `smartcab/agent.py`. Os arquivos `smartcab/enviroment.py`, `smartcab/planner.py`,e `smartcab/simulator.py` são arquivos complementares para o projeto, eles não deverão ser alterados. As imagens estão no arquivo`images`. 


### Run

No terminal dentro do diretorio `smartcab/` (contem no README do projeto), execute os seguintes comandos:

```python smartcab/agent.py```  
```python -m smartcab.agent```

Você vai executar `agent.py`, se estiver tudo certo o algoritimo vai começar a trabalhar é uma janela do PyGame será aberta, você podera ver o modelo trabalhando. Sua função será realizar implementações no modelo afim de melhorar o acerto do modelo.
