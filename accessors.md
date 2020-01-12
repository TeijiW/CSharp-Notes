# Accessors

Métodos responsáveis por interceptarem a obtenção e definição de uma variável

```c#
private int <nome1>

public int <nome2>{
    get{
        // code
        return <nome1>
    }
    set{
        // code
        <nome1> = value
    }
}
```

_value_ é a palavra reservada dentro do accessor _set_ para obter o valor passado para a variável
