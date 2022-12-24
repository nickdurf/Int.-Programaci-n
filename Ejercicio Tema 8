public class Main {
    public static void main(String[] args) {
        Persona persona = new Persona();
        persona.setEdad(27);
        persona.setNombre("Nicolas");
        persona.setTelefono("123-456-7894");
        System.out.println("Nombre: " + persona.getNombre());
        System.out.println("Edad: " + persona.getEdad());
        System.out.println("Telefono: " + persona.getTelefono());
    }

    private static class Persona {
        private int edad;
        private String nombre;
        private String telefono;

        Persona(int edad, String nombre, String telefono) {
            this.edad = edad;
            this.nombre = nombre;
            this.telefono = telefono;
        }

        public Persona() {

        }

        public int getEdad() {
            return edad;
        }
        public void setEdad(int edad) {
            this.edad = edad;
        }

        public String getNombre() {
            return nombre;
        }
        public void setNombre(String nombre) {
            this.nombre = nombre;
        }

        public String getTelefono() {
            return telefono;
        }
        public void setTelefono(String telefono) {
            this.telefono = telefono;
        }
    }
}
