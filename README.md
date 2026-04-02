import java.util.*;
public class Main
{
	public static void main(String[] args) {
	    String name1 = "ravi";
	    int roll1 = 123;
	    String departs1 = "ECE";
	     String name2 = "Sunil";
	    int roll2 = 456;
	    String departs2 = "MEC";
	     String name3 = "Sai";
	    int roll3 = 987;
	    String departs3 = "CSE";
	    
	    Student st1 = new Student(name1,roll1,departs1);
	     Student st2 = new Student(name2,roll2,departs2);
	      Student st3 = new Student(name3,roll3,departs3);

	ArrayList<Student>list = new ArrayList<>();

			System.out.println(st1);
				System.out.println();
				System.out.println(st2);
					System.out.println();
					System.out.println(st3);
	}
}
class Student{
     String name;
	    int roll;
	    String departs;
	    Student(String name,int roll,String departs){
	        this.roll = roll;
	        this.name = name;
	        this.departs = departs;
	    }
	    public String toString(){
	    return "name : "+name+" "+"roll : "+roll+" "+"depart : "+departs;
}}
