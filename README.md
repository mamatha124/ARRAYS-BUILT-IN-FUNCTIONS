# ARRAYS-BUILT-IN-FUNCTIONS
import java.util.Arrays;
class HelloWorld {
    public static void main(String[] args) {
        int []n={6,2,8,1,3,7};
        Arrays.sort(n);
        System.out.println("Sorted Array: "+Arrays.toString(n));
        int[] array1={6,2,8,10,3,7};
        System.out.println("Equal or not Array: "+Arrays.equals(array1,n));
        int i=Arrays.binarySearch(n,8);
         System.out.println("binarySearch: "+i);
        int[] na=Arrays.copyOf(n,6);
         System.out.println("Copying Array "+Arrays.toString(na));
         int []fa=new int[5];
         Arrays.fill(fa,7);
         System.out.println("Filling array: "+Arrays.toString(fa));
        
    }
}
