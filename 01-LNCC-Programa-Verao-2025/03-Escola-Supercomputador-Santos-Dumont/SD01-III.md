# SD01-III- Programação em Shell Script


Professor: Eduardo Lúcio Mendes Garcia (LNCC)
27/01/2025 de 14h às 18h

## Resumo: 
Este é um minicurso voltado a desenvolver a capacidade de usar o sistema operacional através do terminal de comandos em oposição à clicks do mouse. 
Inicia-se com conceitos fundamentais da organização do Unix, seguindo para o formato dos comandos, o fluxo de execução e programação modular com funções.

## Ementa: 
Terminal, Arquivos e diretórios, Comandos, Variáveis, Operações. 
Fluxo de execução, programação modular

## Bibliografia:
- Classic Shell Scripting, por Arnold Robbins, isbn 978-8577801473
- Linux pocket guide daniel j. barret, isbn 978-1449316693
- https://www.geeksforgeeks.org/introduction-to-unix-system/

---

```shell

```



```shell
echo $HOME
```

Variáveis de ambiente
```shell
echo $PS1
```


modificar conteúdo de uma variável

```shell
$ PS1 = fjskajdf      # o sinal "=" é de atribuição
```



escreve o diretório de trabalho atual
```shell
pwd   # Print Working Directory
```


outra variável de ambiente
```shell
echo $PWD
```


```shell
sleep 30
```


busca de string `echo` em um arquivo rodarExperimento.sh
```shell
grep echo rodarExperimento.sh
```

contar as linhas
```shell
grep echo rodarExperimento.sh | wc -l  # Word Count
```

contar os caracteres:
```shell
grep echo rodarExperimento.sh | wc -c
```

contar palavras:
```shell
grep echo rodarExperimento.sh | wc -w
```


```shell
which grep
```



```shell
cd   # Change Directory
```


```shell
cd ..
```











```shell
chmod   #change mood?
```

```shell

```









```shell
ls -a
```

```shell

```