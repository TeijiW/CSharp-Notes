# Delegates

Objeto que pode fazer referência a um ou vários métodos

```c#
    delegate int Calculo(<parâmetros>);

    class Calc{
        public static int soma (<parâmetros>){
            // code
        }
        public static int mult (<parâmetros>){
            // code
        }
    }

    static void Main(){
        Calculo calc1 = new Calculo(Calc.soma);
        Calculo calc2 = new Calculo(Calc.mult);
    }
```
