# activida-semana6
public class indesemana6 {
    String nombre = "Juan Zapata";
    int salarioBase = 45000000;
    int horasTrabajo = 192;
    int horasExtras = 10;
    double auxilioTransporte = 162000;
    // Cálculo de la nómina
    double salarioDevengado = calcularSalarioDevengado(salarioBase, horasTrabajo, horasExtras);n=in.nextlint();in=

    nextlint();

    for(i=1;i<n;i++){
            System.out.println("proceso"+i);
            System.out.println("Juan zapata");
            System.out.println("ingrese el valor del salario minimo ");
            salario minimo = in.nextlint();
            in.nextline
            System.System.out.println("ingrese el valor del sueldo Devengado");
            in.nextline
            in.nextline
            salud = 1.000000
            pensiones =
            seguridad = 

            if (sueldo_devegado<=salario minimo *3)
        }
    {
        salud = sueldo_devengado * 0.05;
        pensiones = sueldo_devengado * 0.118;
        seguridad = sueldo_devengado * 0.03;
    }if(sueldo_devengado>salario_minimo*4&&sueldo_devengado<salario_minimo*8)
    {
        salud = sueldo_devengado * 0.1;
        pensiones = sueldo_devengado * 0.15;
        seguridad = sueldo_devengado * 0.05;
    }if(sueldo_devengado>salario_minimo*8&&salario_minimo<=salario_minimo*20)
    {
        salud = sueldo_devengado * 0.2;
        pensiones = sueldo_devengado * 0.13;
        seguridad = sueldo_devengado * 0.1;
    }nomina=sueldo-Devengado-salud-pensiones;System.out.println("nombre:"+nombre);System.out.println("volar de nomina:"+nomina);System.out.println("valor de pensiones:"+pensiones);System.out.println("valor de salud:"+salud);System.out.println("valor de seguridad:"+seguridad);System.out.println();

    nomina=sueldo_devengado-salud-pensiones-seguridad-guerra;System.out.println("Nombre: "+nombre);System.out.println("Valor de nomina: "+nomina);System.out.println("Valor de pensiones: "+pensiones);System.out.println("Valor de salud: "+salud);System.out.println("Valor de seguridad: "+seguridad);System.out.println();

    double deducciones = calcularDeducciones(salarioDevengado, auxilioTransporte);

    double salarioDevengado = 200000;
    double auxilioTransporte = 162000;
    double deducciones=calcularDeducciones(salarioDevengado,
    double auxilioTransporte);
    double deducciones = 0.0;if(salarioDevengado>2*salario_minimo)
    {
        deducciones -= auxilioTransporte;
    }

    public static double salario_minimo = 1300000; // valor de minimo en colombia (2024)

    double salarioNeto = salarioDevengado - deducciones;

    double salarioDevengado = 200000;
    double auxilioTransporte = 162000;
    double deducciones = calcularDeducciones(salarioDevengado, auxilioTransporte){
        double deducciones = 0.0;

        deducciones = salarioDevengado = 0.9;
        if (salarioDevengado >2* salario_minimo){
            deducciones -=auxilioTransporte;
        }
        return deducciones; 
    }
    public static final double salario_minimo = 408.526; // salario minimo
}

    // Método para calcular el salario devengado
    public static double calcularSalarioDevengado(int salarioBase, int horasTrabajo, int horasExtras) {
        // Implementar solución
        int salarioBase = 45000000;
        int horasTrabajo = 192;
        int horasExtras = 10;
        double salarioDevengado = calcularSalarioDevengado(salarioBase, horasTrabajo, horasExtras);
        System.out.println("Salario Devengado: " + salarioDevengado);
    }

    public static double calcularSalarioDevengado(int salarioBase, int horasTrabajo, int horasExtras) {

        double salarioDevengado = salarioBase + calcularValorHorasExtras(horasExtras);

        if (horasTrabajo < 192) {
            salarioDevengado -= calcularDescuentoHorasFaltantes(salarioBase, horasTrabajo);
        }

        return salarioDevengado;
    }

    public static double calcularValorHorasExtras(int horasExtras) {
        double valorHoraExtra = 2 * 10;
        return horasExtras * valorHoraExtra;
    }

    public static double calcularDescuentoHorasFaltantes(int salarioBase, int horasTrabajo) {
        double porcentajeDescuentoPorHoraFaltante = 0.05; 
        double valorHoraFaltante = salarioBase * porcentajeDescuentoPorHoraFaltante;
        return (10 - horasTrabajo) * valorHoraFaltante;
    }
