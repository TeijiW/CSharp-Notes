# Collections

## List - Lista

-   Dinâmico e ilimitado

### Declaração/Atribuição

-   `var <nome> = new List<tipo>()`

### Métodos

-   `Add(<elemento>)`
-   `AddRange(<collection>)` Adiciona a collection especificada no fim da lista
-   `Clear()`
-   `Contains(<elemento>)` Retorno: _true_ ou _false_
-   `Exists(<predicate>)`
-   `Find(<predicate>)`
-   `FindAll(<predicate>)` Retorno: List com todos os itens que correspondem às condições
-   `FindIndex(<predicate>)` Retorno: index da primeira ocorrência que corresponde às condições, se for encontrado; caso contrário, -1.
-   `FindLast(<predicate>)` Retorno: Último elemento de acordo com as condições
-   `FindLastIndex(<predicate>)` Retorno: Index do último elemento de acordo com as condições
-   `ForEach(<action|predicate>)`
-   `Insert(<index>, <elemento>)` Mais **performático**
-   `Remove(<elemento>)`
-   `RemoveAt(<index>)`
-   `RemoveAll(<predicate>)`
-   `Reverse()`

## Array

-   Tamanho fixo
-   ```c#
      <tipo>[] <variavel>
      <variavel> = new <tipo>[<tamanho>]
    ```

## Dictionary - Dicionário

-   Dinâmico e ilimitado

### Declaração/Atribuição

-   ```c#
     Dictionary<<tipoChaves>, <tipoValores>> <nome> =
         new Dictionary<<tipoChaves>, <tipoValores>>();
    ```
-   `<nome>[<chave>] = <valor>`

### Métodos

-   `Add(<chave>, <valor>)`
-   `Clear()`
-   `Remove(<chave>)`
-   `ContainsKey(<chave>)` Retorno: _true_ ou _false_
-   `ContainsValue(<valor>)` Retorno: _true_ ou _false_
-   `TryAdd(<chave>, <valor>)` -
-   `TryGetValue(<valor>, out <nome>)` Retorno: <nome> sendo o valor ou _false_
