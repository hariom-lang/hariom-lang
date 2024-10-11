class Pen {
    // Private attributes
    private String color;
    private int tip;

    // Getter method for color
    String getColor() {
        return this.color;
    }

    // Getter method for tip
    int getTip() {
        return this.tip;
    }

    // Setter method for color
  public   void setColor(String newColor) {
        this.color = newColor;
    }

    // Setter method for tip
  public  void setTip(int tip) {
        this.tip = tip;
    }
}

public class Oops6 {
    public static void main(String args[]) {
        // Creating a pen object called p1
        Pen p1 = new Pen();
        
        // Setting color and printing it
        p1.setColor("Blue");
        System.out.println(p1.getColor());
        
        // Setting tip and printing it
        p1.setTip(5);
        System.out.println(p1.getTip());
        
        // Changing color and printing it
        p1.setColor("Yellow");
        System.out.println(p1.getColor());
    }
}

