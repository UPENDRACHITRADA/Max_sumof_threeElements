import java.util.*;
public class Main {
    public static void main(String args[]) {
        int arr[] = {2,1,5,1,3,2};
        int max =0;
        for (int i = 0;i<arr.length-2;i++) {
            int sum = arr[i]+arr[i+1]+arr[i+2];
            if(sum>max) {
                max=sum;
            }
        }
        System.out.println(max);
    }
}
