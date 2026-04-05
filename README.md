# $${\color{blue}Guia \space de \space estudos \space de \space IoT \space com \space \color{purple}NotebookLM}$$
Guia de estudos introdutório sobre IoT e algumas aplicações;
## $${\color{blue} Objetivos}$$
- Aprender sobre os fundamentos de IoT com auxílio do $${\color{purple}NotebookLM}$$
- Ver exemplos de projetos e aplicações
- Explorar um pouco sobre o uso da IA no mundo de IoT
## $${\color{violet}Curadoria \space de \space fontes}$$

- https://aws.amazon.com/pt/what-is/iot/
- https://www.ibm.com/br-pt/think/topics/internet-of-things
- https://telemedicinamorsch.com.br/blog/iot-na-medicina?srsltid=AfmBOooKs3ZM9MNsLWzNRxQ1Xu6zFk7hEfji49_c0ktVe38IVSInGpf_
- https://www.fracttal.com/pt-br/blog/as-9-aplicacoes-mais-importantes-da-internet-das-coisas-iot
- https://www.seidor.com/pt-br/blog/integrando-inteligencia-artificial-na-iot-casos-de-uso-e-tendencias
## Engenharia de prompt utilizada no $${\color{purple}NotebookLM}$$
Primeiro eu listei o que eu precisava extrair das fontes (objetivos); <br>
Depois, soliscitei que ele fizesse uma introdução sobre cada tópico; <br>
<br>
Com relação ao Troubleshooting, não tive esse empecilho, acredito que fui preciso nas fontes e prudente nas instruções.<br>
###  $${\color{blue} Prompt:}$$
Preciso de um guia de estudos introdutório sobre alguns tópicos de IoT:<br>
- Aprender sobre os fundamentos de IoT
- Ver exemplos de projetos e aplicações
- Explorar um pouco sobre o uso da IA no mundo de IoT<br>
Dados os tópicos, preciso que gere uma introdução completa e detalhada.<br>

### $${\color{green} Miniguia \space de \space Estudos}$$

Resumos Estruturados
Fundamentos da IoT A Internet das Coisas (IoT) é a rede de dispositivos físicos equipados com sensores e softwares que se conectam à internet para coletar e trocar dados
. O sistema funciona em três pilares:
Dispositivos inteligentes: Coletam dados do ambiente através de sensores
.
Aplicações de IoT: Sistemas (muitas vezes com IA) na nuvem que recebem, processam e analisam os dados
.
Interface do usuário: Aplicativos ou sites usados para gerenciar e controlar os dispositivos
.
Exemplos de Aplicações
Saúde: Uso de dispositivos vestíveis (wearables) para medir sinais vitais
,
, sensores ingeríveis (pílulas com câmera)
 e leitos hospitalares inteligentes
,
.
Cidades e Casas: Aplicativos como Waze usando celulares como sensores de trânsito
 e termostatos inteligentes para eficiência energética
.
Indústria (IIoT) e Logística: Robôs conectados (como os da Amazon) para organização de estoque
 e sensores gerando imagens 3D para montagem de veículos
.
Agricultura e Frotas: Sensores medindo a umidade do solo para otimizar irrigações
,
 e monitoramento de telemetria e combustível de veículos
.
Uso da IA na IoT
Manutenção Preditiva: A IA analisa dados (ex: temperatura ou vibração de um motor) para prever e evitar falhas antes que elas aconteçam
,
.
Detecção de Anomalias: A IA identifica padrões anormais nos dados na própria borda, filtrando falhas em sistemas de ventilação ou comportamentos suspeitos
,
.
Segurança: Câmeras com IA identificam fisicamente comportamentos de risco, enquanto algoritmos bloqueiam tráfego cibernético incomum na rede
.

--------------------------------------------------------------------------------
2. Glossário
Atuadores: Dispositivos que recebem comandos para realizar ações físicas, como fechar válvulas ou ligar motores
.
Computação de Borda (Edge Computing): Processamento de dados realizado fisicamente mais próximo ao dispositivo gerador, reduzindo a latência e o tempo de resposta
.
Computação em Nuvem: Armazenamento e processamento remoto das grandes quantidades de dados gerados pela rede IoT
,
.
IIoT (IoT Industrial): Aplicação da IoT em manufatura, logística e varejo para reduzir custos e aumentar a eficiência dos negócios
,
.
Machine Learning (Aprendizado de Máquina): Algoritmos de IA usados para processar dados de IoT e tomar decisões autônomas em tempo real
.
Manutenção Preditiva: Técnica que antecipa falhas e o tempo de inatividade de máquinas industriais a partir dos dados gerados por sensores
,
.
Sensores: Dispositivos centrais da IoT que detectam alterações físicas do ambiente (ex: luz, pressão, movimento)
,
.
Wearables (Dispositivos Vestíveis): Aparelhos corporais conectados (como smartwatches) que coletam dados e monitoram a saúde dos usuários
,
.

--------------------------------------------------------------------------------
3. Prompts Reutilizáveis (Para Revisão)
"Explique brevemente os 3 componentes centrais de um sistema IoT (dispositivos inteligentes, aplicações de IoT e interface de usuário)
,
."
"Como as tecnologias de Computação em Nuvem e Computação de Borda se complementam no funcionamento da IoT?
,
"
"Cite três exemplos práticos de como a IoT Industrial (IIoT) otimiza os setores de manufatura e logística
,
."
"Resuma o uso da IoT na área médica, detalhando os benefícios de wearables e sensores ingeríveis
,
."
"De que maneira a Inteligência Artificial processa os dados da IoT para atuar na manutenção preditiva industrial e na segurança cibernética?
