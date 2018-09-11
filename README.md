/*
 * Practica para evaluar el impacto de los tipos de datos en la construcciÃ³n
 * del programa
 */

/**
 *
 * @author Javier Octavio
 */
public class Principal {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        // DECLARACIÃ“N DE UN ARREGLO --> lista de variables del mismo tipo
        int[] iArreglo = new int[100000000]; //UN ARREGLO DE 4GB
        byte[] iArregloByte = new byte [302021600]; //UN ARREGLO DE 1GB
        System.out.println("Hola Mundo" + iArregloByte);
    }
    
}
