# Argumentos Especiais nos Métodos

## _Out_

Quando passado para um método, será responsável por retornar um outro valor (além do _return_)

```c#
public static void teste(int num1, out int num2){
    // code
    return num1
}

teste(<valorQualquer>, out <variavel>)
```

No código acima, _variavel_ receberá o valor da saída de _num2_

## params

Usado para um número indeterminado de parâmetros

```c#
    public static void soma(params <tipo>[]<nome>){
        // code
    }
```
