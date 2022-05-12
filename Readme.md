# CALCULADORA BASICA CON MENU

Una calculadora basica se puede realizar con condiciones. Se desea realizar alguna de las operaciones basicas con numeros `x, y`. Ademas se desea calcular la pitencia y el logaritmo. Se deben de considerar los casos donde `y = 0`donde ka division `x/y` NO se puede calcular el `log(x)`. Se desea generar un menu para que el usuario pueda seleccioar la operacion a realizar. Una manera de hacerlo es la sigiente

1. Se reciben los dos numeros `x, y` para realizar la oeracion 
2. Se recibe la operacion a realizar mediante la variable `opcion` la que selecciona en el menu que operacion ejecuta el algoritmo
3. Se inicializa la variable logica `bandera = false`. Si la division o el logaritmo no se puedem calcular , se hace `bandera = True`.
4. Mediante condiciones se realiza la operacion deseada
    * En el caso de la division, si `y = 0`,No se puede realizar la division, se muestra un mensaje y se hace bandera `bandera = True`
    * En el caso del logaritmo, si `x <= 0` 