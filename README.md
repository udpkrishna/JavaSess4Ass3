# JavaSess4Ass3

package Basic;

public class Sess4Ass3 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		Encapsulationdemo obj=new Encapsulationdemo();
		obj.setEmpName("James");
		obj.setEmpAge(37);
		
		System.out.println("Employee Name is "+ obj.getEmpName());
		System.out.println("Employee Age is "+ obj.getEmpAge());

	}

}

package Basic;

public class Encapsulationdemo {

	private String empName;
	private int empAge;
	
	public String getEmpName() {
		return empName;
	}
	public void setEmpName(String empName) {
		this.empName = empName;
	}
	public int getEmpAge() {
		return empAge;
	}
	public void setEmpAge(int empAge) {
		this.empAge = empAge;
	}
	
	
}

