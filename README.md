tanker
======
import javax.swing.JOptionPane;

public class tanker {
	public static void main(String[] args){
		String name = JOptionPane.showInputDialog("What is your name?");
		String year = JOptionPane.showInputDialog("What year were you born?");
		String month = JOptionPane.showInputDialog("What month were you born?");
		String date = JOptionPane.showInputDialog("What day were you born?");
		String life = JOptionPane.showInputDialog("how many years will you live?");
		String drink = JOptionPane.showInputDialog("What do you drink?");
		String oz = JOptionPane.showInputDialog("how many ounces of " + drink + " do you drink a day?");
		int LifeExp = Integer.parseInt(life);
		int Oz = Integer.parseInt(oz);
		
		
		JOptionPane.showMessageDialog(null, "If you drink " + oz + " ounces of " + drink + " everyday, you will drink about " + ((LifeExp*Oz*360.0)/1024000.0) + " 8000 Gallon Tanker Trucks worth of " + drink + " in your lifetime.");
	}}
	

