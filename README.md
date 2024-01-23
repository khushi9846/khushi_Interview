# khushi_Interview

// Online Java Compiler
// Use this editor to write, compile and run your Java code online

class FactorialCalculator {
       static int n=4;
    public static void main(String[] args) {
         
 //Here we are calling the function and taking its return value in an long variable.
       long result=calculateFactorial(n);
         
         //Then printing the result.
         System.out.print(result); 
         
         
    }
    public static long calculateFactorial(int n){
    //initial value for factorial is set to 1.
       int factor=1;
         System.out.println("Hello, the factorial of "+ n +" is: ");
         
         //A check for input 0 is put here , if so then the result will be 1 as 0!=1
         if(n==0){
             return 1;
         }
         else{
         //In the else block the logic for factorial  is written.
         //by looping ,we'll calculate the scenario 
         //eg: 4!= 4*3*2*1 , here by using for loop we'll do the same.
         
         for(int i=1;i<=n;i++){
             factor=factor*i;
         }
         }
         return factor;
    }
}
