# Introdução à Programação CUDA

Professora: Denise Stringhini (UNIFESP)

## Resumo: 
Curso introdutório em linguagem CUDA, uma extensão da linguagem C utilizada para a programação de aplicações de propósito geral, sendo executadas em arquitetura massivamente paralela de placas gráficas, denominadas GPU.

## Objetivos: 
A arquitetura das GPUs (“Graphics Processing Unit”) foi projetada para efetuar os cálculos em ponto flutuante mais frequentemente realizados em aplicações gráficas. Esta é uma arquitetura bem mais especializada que a presente em CPUs (“Central processing unit”) , o que faz com que estes programas rodem mais rapidamente nestas plataformas. Além disso, as GPUs são altamente paralelizadas, já havendo atualmente modelos com milhares de núcleos computacionais (“cores”). Embora originalmente desenvolvida para executar aplicações gráficas com maior eficiência, também é cada vez maior o uso de GPUs em aplicações não-gráficas. São aplicações que envolvem a resolução de métodos de álgebra numérica computacional, frequentemente também utilizados nas aplicações gráficas, obtendo-se um significativo ganho de desempenho. Neste curso será apresentada a arquitetura de placas gráficas NVIDIA e a conexão destas placas com o computador hospedeiro. Em seguida será apresentado a plataforma de programação CUDA, que é uma extensão do C/C++ processada tanto no computador hospedeiro quanto nas placas gráficas conectadas a este. Serão apresentados exemplos de códigos de cada um dos tópicos abordados, os quais os alunos poderão executá-los nas máquinas disponíveis em sala de aula.

## Ementa:
Introdução (Arquitetura)
Modelo de Paralelismo em CUDA
Organização e Identificação
Atribuição
Escalonamento
Hierarquia de Memória
Métricas desempenho e otimização
Estudo de caso: multiplicação de matrizes


## Bibliografia:
CUDA by Example: An Introduction to General Purpose GPU Programming, by David Weller
Programming Massively Parallel Processors: A Hands-on Approach (Applications of GPU Computing Series), by David B. Kirk and Wen-mmei W. Hwu- Second Edition
http://docs.nvidia.com/cuda/cuda-cprogramming-guide/index.htm
http://devblogs.nvidia.com/parallelforall

---


[Slides](https://docs.google.com/presentation/d/1YI4W_k6LqEl25HYuh0Im_Ut2ucrF30D739EPl85WSbU/edit#slide=id.p1)

[Colab](https://colab.research.google.com/drive/1WPSDJ_FU8w1izldk2xRO15EyGKbArw1J?usp=sharing)

---