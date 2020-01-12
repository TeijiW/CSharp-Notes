# Classes

```c#
    <modificadores> class <nome> {
        // propriedades/atributos
        <especificador> <nome>
        // métodos
        <especificador> <tipoRetorno> <nome>(args){
            // code
        }
    }
```

## Modificadores

-   _public_: Sem restrição de visualização
-   _abstract_: Classe base para outras classes, não podem ser instanciados objetos nesta classe
-   _sealed_: Não pode ser herdada
-   _static_: Não permite instanciação de objetos e nem classe construtora. Seus membros devem ser _static_

## Especificadores

-   _public_: Sem restrição de acesso
-   _private_: Podem ser acessados **somente** pela classe criadora
-   _protected_: Podem ser acessados na classe **criadora e nas derivadas**

### Apenas para métodos

-   _abstract_: Os métodos não tem implementação, somente o cabeçalho
-   _sealed_: Não pode ser redefinido, também não pode ser herdada
-   _virtual_: O método pode ser redefinido em uma classe derivada
-   _static_: O método pode ser chamado **sem ser instanciado**
