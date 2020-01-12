# Expcetions

Tratamento de exceções (erros) durante a execução do programa

## Try | Catch | Finally

```c#
    try{
        // code
    }catch(Exception error){
        // code for Exception (error)
        Console.WriteLine(error.message);
    }finally{
        // code for finally
    }
```

_catch_ pode receber tipos específicos de _Exception_ ou apenas ser genérico

## Throw

Combinado com `new Exception()` gera um erro que será pego pelo `catch`

```c#
    try{
        // code
        throw new Exception("Teste");
    }catch(Exception error){
        // code for Exception (error)
        Console.WriteLine(error.message);
    }finally{
        // code for finally
    }
```
