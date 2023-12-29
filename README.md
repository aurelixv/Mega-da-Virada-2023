# Mega da Virada 2023

Gerador de jogos da mega sena da virada de 2023.

### Como Configurar?

\*** Pré-requisito: possuir Python 3 instalado na máquina \***


1. Clone este repositório

```shell
$ git clone <link>
```

2. Entre na pasta do projeto

```shell
$ cd <pasta/mega-da-virada-2023>
```

3. Crie uma venv

```shell
$ python3 -m venv venv
```

4. Ativar a venv

```shell
$ source venv/bin/activate
```

5. Instale os pacotes necessários

```shell
$ pip install -r requirements.txt
```

### Como Gerar?

1. Alimente o arquivo com os seus números da sorte, que podem ser de qualquer tamanho;
2. Rode o notebook fornecendo como parâmetro a quantidade de jogos a serem gerados;
3. Agora é só pegar os jogos e torcer!

### Como funciona o algoritmo?

1. Lê todos os números fornecidos no arquivo 'numeros-da-sorte' e os armazena em uma lista;
2. Quebra cada um desses números e gera combinações entre eles
   - Exemplo: número 123 resultará em 1, 12, 13, 2, 21, 23, 3, 31, 32;
3. Gera jogos aleatórios com base nos números da sorte
   - Números da sorte que aparecem mais terão mais chance de aparecer e vice-versa;
4. Salva os jogos em arquivo 'jogos-da-sorte'
