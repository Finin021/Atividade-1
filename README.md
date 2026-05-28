# Sistemas Evolutivos e Aplicados à Robótica — YOLO26

## Sobre o Projeto

Este projeto apresenta um estudo comparativo entre diferentes modelos da família **YOLO26**, desenvolvidos pela **Ultralytics**, com foco em tarefas de **detecção de objetos** utilizando técnicas de **Visão Computacional** e **Inteligência Artificial**.

O objetivo principal é analisar o comportamento das diferentes arquiteturas YOLO em relação aos seguintes fatores:

-  Velocidade de inferência
-  Desempenho computacional
-  Precisão na detecção de objetos
-  Capacidade de reconhecimento em cenários complexos

---

# Tecnologias Utilizadas

As seguintes tecnologias foram utilizadas durante o desenvolvimento do projeto:

- Python
- YOLO26
- Ultralytics
- OpenCV
- Visão Computacional
- Inteligência Artificial

---

# Modelos Utilizados

Os seguintes modelos da família YOLO26 foram analisados durante os experimentos:

| Modelo | Categoria |
|---|---|
| YOLO26n | Nano |
| YOLO26s | Small |
| YOLO26m | Medium |
| YOLO26l | Large |
| YOLO26x | Extra Large |

---

# Metodologia

Os experimentos foram realizados seguindo as seguintes etapas:

1. Download automático dos modelos YOLO26;
2. Carregamento da imagem de teste;
3. Execução da inferência utilizando cada modelo;
4. Coleta do tempo de processamento;
5. Análise dos objetos detectados.

Todos os modelos foram testados utilizando o mesmo cenário e a mesma imagem de entrada, garantindo igualdade nas comparações realizadas.

---

# Objetos Detectados

Durante os testes, foram identificados diferentes tipos de objetos, incluindo:

- Pessoas
- Bicicletas
- Bolsas
- Animais

---

# 📊 Resultados Obtidos

| Modelo | Tempo de Inferência | Objetos Detectados |
|---|---|---|
| YOLO26n | 0.1359s | 8 pessoas e 1 vaca |
| YOLO26s | 0.3469s | 10 pessoas, 2 bicicletas, 1 vaca e 1 bolsa |
| YOLO26m | 1.4579s | 11 pessoas, 1 bicicleta, 1 vaca e 1 bolsa |
| YOLO26l | 1.1959s | 13 pessoas, 1 bicicleta, 1 vaca e 1 bolsa |
| YOLO26x | 2.4993s | 13 pessoas, 1 bicicleta, 1 vaca e 1 bolsa |

---

# Conclusão

Os resultados obtidos demonstram que modelos maiores possuem maior capacidade de detecção e reconhecimento de objetos, porém exigem maior poder computacional e maior tempo de processamento.

Por outro lado, modelos menores, como o **YOLO26n**, apresentam excelente desempenho para aplicações em tempo real devido à sua alta velocidade de inferência.

Dessa forma, a escolha do modelo ideal depende diretamente do cenário de aplicação e dos requisitos computacionais do sistema.

---

# Como Executar o Projeto

## Instalação das Dependências

```bash
pip install ultralytics opencv-python
````

---

## Executando o Projeto

Após instalar as dependências, execute o arquivo principal do projeto:

```bash
python main.py
```

---

# Teste do Código

O arquivo principal do projeto foi disponibilizado com o nome:

```bash
main.py
```

Você pode executar o código e testar todos os modelos YOLO26 diretamente em seu computador para visualizar os resultados das detecções e comparar o desempenho entre os modelos analisados.

---

# 📖 Referências

* Ultralytics — YOLO26
* OpenCV Documentation
* Python Documentation


