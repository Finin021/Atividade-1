# 🚀 Sistemas Evolutivos e Aplicados à Robótica — YOLO26

## 📌 Sobre o Projeto

Este projeto apresenta um estudo comparativo entre diferentes modelos da família YOLO26, desenvolvidos pela Ultralytics, com foco em tarefas de detecção de objetos utilizando Visão Computacional e Inteligência Artificial.

O objetivo principal é analisar o comportamento de diferentes arquiteturas YOLO em relação a:

- Velocidade de inferência
- Desempenho computacional
- Precisão na detecção de objetos
- Capacidade de reconhecimento em cenários complexos

---

# 🧠 Tecnologias Utilizadas

- Python
- YOLO26
- Ultralytics
- OpenCV
- Visão Computacional
- Inteligência Artificial

---

# 📚 Modelos Utilizados

Os seguintes modelos foram analisados durante os testes:

| Modelo | Descrição |
|---|---|
| YOLO26n | Nano |
| YOLO26s | Small |
| YOLO26m | Medium |
| YOLO26l | Large |
| YOLO26x | Extra Large |

---

# ⚙️ Metodologia

Os experimentos seguiram as seguintes etapas:

1. Download automático dos modelos YOLO
2. Carregamento da imagem de teste
3. Execução da inferência
4. Medição do tempo de processamento
5. Análise dos objetos detectados

Todos os modelos foram testados utilizando o mesmo cenário para garantir igualdade nas comparações.

---

# 🖼️ Objetos Detectados

Durante os testes, foram identificados:

- Pessoas
- Bicicletas
- Motocicletas
- Automóveis
- Caminhões
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

# 📈 Conclusão

Os testes demonstraram que modelos maiores apresentam maior capacidade de detecção e reconhecimento de objetos, porém exigem maior tempo de processamento.

Já os modelos menores, como o YOLO26n, oferecem excelente desempenho para aplicações em tempo real devido à sua velocidade de inferência reduzida.

A escolha do modelo ideal depende diretamente do cenário de aplicação e dos requisitos computacionais do sistema.

---

# ▶️ Como Executar o Projeto

## 1️⃣ Clone o repositório

```bash
git clone https://github.com/SEU-USUARIO/atividade-1-yolo26.git
