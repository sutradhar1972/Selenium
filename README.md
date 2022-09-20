# Selenium
import java.util.ArrayList;
import java.util.List;

public class ObjArr {

	public static void main(String[] args) {

		Object[] obj = new Object[5];
		obj[0] = "Employee";
		obj[1] = 04;
		obj[2] = 1200.00;
		obj[3] = true;
		obj[4] = "E";

		for (int i = 0; i < obj.length; i++) {
			System.out.println(obj[i]);
		}

		for (Object i : obj) {
			System.out.println(i);
		}

	}

}
