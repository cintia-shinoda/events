# SD05-I - Introdução a Workflows Científicos Paralelos em Python/Parsl

### Professor: 
Diego Carvalho (CEFET-RJ)

### Ementa:
1.  Introdução geral à HPC
2. Processamento em memória compartilhada
   - Threads vs processos
   - Módulo threading vs módulo multiprocessing
3. Módulo multiprocessing
   - Exemplo: aproximação de $\pi$ com Monte Carlo
4. Processamento em memória distribuída
   - Introdução à MPI
   - Módulo mpi4pi
   - Módulo mpi4pi + módulo numpy
   - Exemplo: reimplementação da aproximação de $\pi$ com MPI
5. Biblioteca Parsl

https://github.com/diegomcarvalho/LNCC-ProgramaVeraoSD

---

## Documentação

https://parsl-project.org/
https://parsl.readthedocs.io/en/stable/

## Instalação
```bash
pip install parsl
```


##
```python

```

## Bash Apps
- tarefas do Parsl para aplicações externas
- não retornam valores
- sincronização via ```result()``` e ```done()```
- podem se comunicar através de arquivos (parâmetros especiais)
- dependências automáticas são criadas em ```future.result()```

```python
@bash_app
```

## DataFutures

```python

```

## Ambiente
- Memória e ```Name Space``` não são necessariamente compartilhados entre a aplicação principal e as tarefas

```python

```


## Arquivos


## ```Parsl Executor```

## 


---

## Parsl no Santos Dumont