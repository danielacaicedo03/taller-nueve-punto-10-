public class Empleado {
 
	private String nombre;
	private int direccion;
	private Integer salario;
	private int telefono;
	
	public Empleado(String nom, int ape, int tel, Integer sal) {
		nombre = nom;
		direccion = ape;
		salario = sal;
		telefono = tel;
	}
 
	public String getNombre() {
		return nombre;
	}
 
	public int getDireccion() {
		return direccion;
	}
 
	public Integer getSalario() {
		return salario;
	}
 
	public void setSalario(Integer sal) {
		salario = sal;
	}
 
	@Override
	public String toString() {
		return String.format("%s %s %s --> %d€", nombre, direccion, telefono, salario);
	}
}
