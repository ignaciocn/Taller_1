# Taller_1
-Repositorio taller 1 Programación orientada a objetos
-Aplicacion para calcular salario bruto a liquido
**Sebastian Rehbein**
**Ignacio Nuñez**
 * Calculadora que recibe los datos del salario bruto, Afp, prevision, salud, gratificacion.
     * @param salarioBruto
     * @param afp
     * @param prevision
     * @param salud
     * @param gratificacion
public class CalculadoraSalario {
    public double salarioBruto;
    public double afp;
    public double prevision;
    public double salud;
    public double gratificacion;
/**
 * Calculadora que recibe los datos del salario bruto, Afp, prevision, salud, gratificacion.
     * @param salarioBruto
     * @param afp
     * @param prevision
     * @param salud
     * @param gratificacion
 */
  public CalculadoraSalario(double salarioBruto, double afp, double prevision, double salud, double gratificacion){
      this.salarioBruto = salarioBruto;
      this.afp = afp;
      this.prevision = prevision;
      this.salud = salud;
      this.gratificacion = gratificacion;
    }
  
}
