# Matrix


public class MatrixApp {
    
    public static void main (String[] args){
        Matrix a = new Matrix();
        Matrix b = new Matrix();
        Matrix sum = new Matrix();
   
        System.out.println("Matrix Magic!");
        System.out.print("----------\n");
        a.setCell(0, 0, 10);
        a.setCell(0, 1, 20);
        a.setCell(0, 2, 30);
        a.setCell(0, 3, 30);
        
        a.setCell(1, 0, 10);
        a.setCell(1, 1, 20);
        a.setCell(1, 2, 30);
        a.setCell(1, 3, 30);
        
        a.setCell(2, 0, 10);
        a.setCell(2, 1, 20);
        a.setCell(2, 2, 30);
        a.setCell(2, 3, 30);
        
        a.setCell(3, 0, 10);
        a.setCell(3, 1, 20);
        a.setCell(3, 2, 30);
        a.setCell(3, 3, 30);
        a.displayMatrix();
        
        System.out.print("----------\n");
        b.setCell(0, 0, 10);
        b.setCell(0, 1, 20);
        b.setCell(0, 2, 30);
        b.setCell(0, 3, 30);
        
        b.setCell(0, 0, 10);
        b.setCell(0, 1, 20);
        b.setCell(0, 2, 30);
        b.setCell(0, 3, 30);
        
        b.setCell(0, 0, 10);
        b.setCell(0, 1, 20);
        b.setCell(0, 2, 30);
        b.setCell(0, 3, 30);
        
        b.setCell(0, 0, 10);
        b.setCell(0, 1, 20);
        b.setCell(0, 2, 30);
        b.setCell(0, 3, 30);
        b.displayMatrix();
       
        System.out.print("----------\n");
        sum.addMatrices(a, b);
        sum.displayMatrix();
        
    }
}
