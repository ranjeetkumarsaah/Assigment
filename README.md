# Assigment
public class SumOfseries {
    public static int sumSeries(int n){
        if(n==0){
            return 0;
        }
            if(n%2==0){
             return sumSeries(n-1)-n;
            }
            else{
                return sumSeries(n-1)+n;
            }
        }
    
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        System.out.println("please enter the elemnt:");
        int n=sc.nextInt();
        System.out.println(sumSeries(n));
    }
    
}
