public class Main {
    public static void main(String[] args) {

        System.out.println("Ciclo infinito");
        int contadorInfinito = 1;

        while (contadorInfinito <= 3) {
            System.out.println("Esto se repetiria siempre");

            {
                while (contadorInfinito <= 3){
                    System.out.println("Iteracion corregida numero:" + contadorInfinito);
                    contadorInfinito++;
                }
                System.out.println("----------------------");

                System.out.println("Control de limites e  arreglos");
                int[] numeros ={10, 20, 30 ,40, 50};
                for (int i = 0; i < numeros.length; i++){
                    System.out.println("Indice ["+ i +"] =" + numeros[i]);
                }

            }
            System.out.println("Arreglo recorrido con exito sin errores de limites");
        }
    }
}