# bubbleSort
import java.util.*;
class Main {
  public static void main(String[] args) {
    Scanner sc = new Scanner(System.in);
    int n = sc.nextInt();
    int[] arr = new int [n];
    for(int i=0;i<n;i++){
      arr[i] = sc.nextInt();
    }
    sc.close();
    int flag =0;
    int temp;
    
        for(int i=0;i<n;i++){
          
            for(int j=1;j<n-i;j++){
                if(arr[j-1]>arr[j]){
                   temp = arr[j-1] ;
                    arr[j-1] = arr[j];
                   arr[j] = temp;
                  flag++;
                }
            }
        }
    if(flag==0){
            System.out.println("Already sorted");
          }
    System.out.println("no of swaps "+flag);
    for(int i=0;i<n;i++){
    System.out.print(" " +arr[i]);
    }
    }
  }
