Write a program to display the month of a year. Months of the year should be held in an array.



import java.util.Calendar; 

public class Demo {

public static void main(String[] args)

{

Calendar calendar = Calendar.getInstance();

String[] month = new String[] {"January", "February", "March", "April",

 "May", "June",

"July", "August","September", "October", "November", "December" };

 System.out.println("Current Month = " + month[calendar.get(Calendar.MONTH)]);

}

}



