# Calculadora
## Passo a passo

* 1 - Digitar o primeiro número
* 2 - Digitar o segundo número
* 3 - Escolher o Tipo de operação
* 4 - Tela de resultado
  
### Solicitando ao usuário os números
- num1 = float(input('Digite o primeiro número: '))
- num2 = float(input('Digite o segundo número: '))

### Vamos utilizar as 4 operação matematicas, soma, sutração, multiplicação ou divisão.
- soma = num1 + num2
- sub = num1 - num2
- mult = num1 * num2
- div = num1 / num2

### Pedir ao usuário que escolha a operação
- (print('\nQual operação você deseja realizar? Selecione:'))
- operacao = int(input(' 1 - Soma \n 2 - Subtração\n 3 - Multiplicação\n 4 - Divisão\n Operação escolhida = '))


### Vamos fazer a condicional para cada operação
- if operacao == 1:
-  print('\nEscolheu a soma, resultando em: ', soma)
- elif operacao == 2:
-   print('\nEscolheu a subtração, resultando em: ', sub)
- elif operacao == 3:
-  print('\nEscolheu a multiplicação, resultando em: ', mult)
-elif operacao == 4:
-  print('\nEscolheu a divisão, resultando em: ', div)
-else:
-  print('\nOpção Inválida. Tente Novamente! \nLembrando que só aceitamos 1, 2, 3 ou 4!')

# Usando o arquivo shell
### Pré-requisitos

- Sistema Operacional: O script foi desenvolvido e testado no Linux. Pode funcionar em outros sistemas UNIX-like como macOS.
- Permissões: Veja se você tem permissões de execução para o arquivo shell.
- Dependências: Verifique se todas as dependências mencionadas no projeto estão instaladas.

### Passo a passo
- 1. Navegue até o diretório do projeto, abrindo o terminal. Por exemplo:
     cd /caminho/projeto
- 2. Verique as permissões do arquivo Shell. Caso não tenha, fazer por exemplo:
    chmod +x seu_script.sh
- 3. Execute. Por exemplo:
     ./seu_script.sh
     
     
