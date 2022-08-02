# part2practical1


package part2;

public class Circle {
		
	 double radius=1; 
		double Area; 
		double Perimeter; 
		Circle() 
		{ 
			radius =10; 
		} 
		
		Circle(double r) 
		{ 
			radius = r; 
		} 
		
    double getarea() 
    { 
        Area = 3.14 * radius;
        return Area;
	  }

	double getPerimeter()
	{
		Perimeter = 2 * 3.14 * radius;
		return Perimeter;
	}

	public static void main(String... args)
	{
		Circle C1 = new Circle();
	    
		System.out.println("Area= "+C1.getarea());
		System.out.println("Perimeter= "+C1.getPerimeter());
		
		Circle C2 = new Circle(5);
		System.out.println("Area= "+C2.getarea());
		System.out.println("Perimeter= "+C2.getPerimeter());
	}
	
	}


