# -17
практическая 18
public class Pr1817 { 
public static void main(String[] args) { 
Scanner a = new Scanner(System.in); 
System.out.print("Стоимость минуты разговора: "); 
double Sm = a.nextDouble(); 
System.out.print("Длительность разговора: "); 
double M = a.nextDouble(); 
System.out.print("День недели: "); //1 - понедельник, ..., 7 - воскресенье 
int Day = a.nextInt(); 
 
double S = Sm * M; 
 
if (Day <= 7) { 
double Ss = S * 0.8; 
System.out.println("Стоимость разговора с учётом скидки: " + Ss); 
} else { 
System.out.println("Стоимость разговора: " + S); 
} 
 
} 
} 
 
