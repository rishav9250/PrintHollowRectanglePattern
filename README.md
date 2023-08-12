# PrintHollowRectanglePattern
here is a code of PrintHollowRectanglePattern in java.



public class PrintHollowRectanglePattern {
    public static void HollowRectangle(int row , int column){
        for(int i =1;i<=row;i++){
            for(int j =1;j<=column;j++){
                if(i==1||i==row||j==2||j==column){
                    System.out.print(" *");
                }
            else{
                System.out.print(" ");
            }
        }
       System.out.println();
            }
        }
        
    public static void main(String[] args) {
        HollowRectangle(4,5);
    }
    }



