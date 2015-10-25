# Matrix

public class Matrix {
    private final int SIZE = 4;
    private final int [][] squares = new int[SIZE][SIZE];
    public Matrix(){}

    Matrix(int x, int y) {
        throw new UnsupportedOperationException("Not supported yet.");
    }
    public void addMatrices(Matrix a, Matrix b){
    
        int x, y;
        for(x = 0; x < SIZE; x++){
            for(y = 0; y < SIZE; y++){
                squares[x][y] = a.getCell(x,y) + b.getCell(x,y);
            }
                
        }
    }
    public int getCell(int x, int y){
        return this.squares[x][y];
    }
    public void setCell (int x, int y, int value){
        squares[x][y] = value;
    }
    public void displayMatrix(){
        int x,y;
        for (x = 0; x < SIZE; x++){
            for (y = 0; y < SIZE; y++){
                showCell(x,y);
            }
            System.out.println("");
        }
    }
    public void showCell (int x, int y){
        System.out.println(squares[x][y] + " ");
    }
}
