# java-
//Java code for print patterns
/*
1
1 2
1 2 3
1 2 3 4
*/

 
public class num {
     public static void printNums(int n)
    {
        // initialising starting number
        int i, j, num=1;
         
        // outer loop to handle number of rows
        // n in this case
        for(i=0; i<n; i++)
        {
 
            // without re assigning num
            // num = 1;
            for(j=0; j<=i; j++)
            {
                // printing num with a space
                System.out.print(num+" ");
                 
                // incrementing num at each column
                num = num + 1;
            }
 
            // ending line after each row
            System.out.println();
        }
    }
     
    // Driver Function
    public static void main(String args[])
    {
        int n = 5;
        printNums(n);
    }
}
