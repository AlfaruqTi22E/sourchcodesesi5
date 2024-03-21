class ModifierExample {
    // Modifier access
    public int publicVar = 1;
    protected int protectedVar = 2;
    private int privateVar = 3;

    // Modifier non-access
    static int staticVar = 4;
    final int finalVar = 5;

    // Metode dengan modifier access
    public void publicMethod() {
        System.out.println("Public Method");
    }

    protected void protectedMethod() {
        System.out.println("Protected Method");
    }

    private void privateMethod() {
        System.out.println("Private Method");
    }

    // Metode dengan modifier non-access
    static void staticMethod() {
        System.out.println("Static Method");
    }

    final void finalMethod() {
        System.out.println("Final Method");
    }
}

public class Main {
    public static void main(String[] args) {
        ModifierExample example = new ModifierExample();

        // Akses ke variabel public
        System.out.println(example.publicVar);

        // Akses ke variabel protected
        System.out.println(example.protectedVar);

        // Akses ke variabel private tidak mungkin dilakukan dari luar kelas
        // System.out.println(example.privateVar); // Akan menghasilkan error

        // Akses ke variabel static tanpa instance
        System.out.println(ModifierExample.staticVar);

        // Akses ke metode public
        example.publicMethod();

        // Akses ke metode protected
        example.protectedMethod();

        // Akses ke metode private tidak mungkin dilakukan dari luar kelas
        // example.privateMethod(); // Akan menghasilkan error

        // Akses ke metode static tanpa instance
        ModifierExample.staticMethod();

        // Akses ke metode final
        example.finalMethod();
    }
}
