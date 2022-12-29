public class Main {
    public static void main(String[] args) {
        Cliente cliente = new Cliente();
        Trabajador trabajador = new Trabajador();

        cliente.edad = 27;
        cliente.telefono = "123-456-7879";
        cliente.nombre = "Nicolas";
        cliente.credito = 2100.50;
        System.out.println("Soy un cliente. Mi nombre es " + cliente.nombre + ", tengo " + cliente.edad +
                " años y mi teléfono es " + cliente.telefono + ". Tengo un crédito disponible de " +
                cliente.credito + " USD.");

        trabajador.edad = 25;
        trabajador.telefono = "789-456-1212";
        trabajador.nombre = "Carlos";
        trabajador.salario = 5000.50;
        System.out.println("Soy un trabajador. Mi nombre es " + trabajador.nombre + ", tengo " + trabajador.edad +
                " años y mi teléfono es " + trabajador.telefono + ". Tengo un salario de " +
                trabajador.salario + " USD.");
    }
}

class Persona {
    int edad;
    String nombre;
    String telefono;
}

class Cliente extends Persona {
    double credito;
}

class Trabajador extends Persona {
    double salario;
}
