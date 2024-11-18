# Array.java
public class arry {
    public static void main(String[] args) {
        int[]moneys ={12,87,987,646,665,345,4567,55};
        System.out.println(moneys[0]);
        System.out.println(moneys[1]);
        System.out.println(moneys[2]);
        System.out.println(moneys[6]);
        System.out.println(moneys[7]);
        System.out.println(moneys[5]);

        System.out.println("print output of arry using loop");

        for(int i=0;i<7;i++){
            System.out.println(moneys[i]);


            //2d arry
            int[][]numbers ={{11,12},{22,34},{665,456},{49,256},{789,366},{78,25},{45,26}};
            System.out.println(numbers[0][0]);
            System.out.println(numbers[0][1]);
            System.out.println(numbers[1][0]);
            System.out.println(numbers[1][1]);
            System.out.println(numbers[6][0]);

            System.out.println("using loop");

            for(int j=0;j<7;j++){
                for(int k=0; k<2;k++){
                    System.err.println(numbers[j][k] + " ");

                }
                System.out.println();
            }
        }
        
        
