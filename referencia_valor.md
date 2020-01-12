# Passagem por Referência e Valor

Ao passar uma variável para um método (por exemplo), é passado o valor da variável, mas não sua referência.

`metodoExemplo(variavel);`

Para passar a referência do endereço da variável na memória, é necessário utilizar a palavra reservada _ref_

`metodoExemplo(ref variavel);`

**Observação:** É necessário que o método espere receber uma referência.

```c#
    public static void metodoExemplo(ref <tipo> <variavel>){
        //code
    }
```
