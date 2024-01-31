# array-
// import java.util.*;
// class Main { 
//   public static void main(String[] args) 
//   {
//       int x;
//       int  sum = 0;
//       float average;
//       Scanner s = new Scanner(System.in);
//       System.out.print("Enter x");
//       x = s.nextInt();
//       int a[] = new int[x];
//       System.out.println("input numbers");
//       for(int i = 0; i < x ; i++)
//       {
//           a[i] = s.nextInt();
//           sum = sum + a[i];
//       }
//       average = sum / x;
//       System.out.println("Average:"+average);
//   }
//  }



// import java.util.*;
// class Main { 
//   public static void main(String[] args) 
//   {
// int x;
//       Scanner s = new Scanner(System.in);
//       System.out.print("Enter inputes number ");
//       x = s.nextInt();
//       int a[] = new int[x];
//       System.out.println("input numbers");
//       for(int i = 0; i < x; i++)
//       {
//           a[i] = s.nextInt();
//       if (a[i]%2== 0)
//       {
//         System.out.println("even number is "+even);
//       }
//       else
//       {
//           System.out.println("odd");
//       }
//       }
//   }
//  }



// import java.util.*;
//  class Main{  
//  public static void main(String args[]){  
//   System.out.print("Enter inputs number ");
//    Scanner s = new Scanner(System.in);
//         int x = s.nextInt();
//         int a[] = new int[x];
//         System.out.println("input numbers");
//         for(int i = 0; i < x; i++)
//         {
//             a[i] = s.nextInt();
//         }
//         System.out.println("Odd Numbers:");  
//        for(int j=0;j<a.length;j++){  
//           if(a[j]%2!=0){  
//               System.out.println(a[j]);  
//             }  
//           }  
//            System.out.println("Even Numbers:");  
//          for(int k=0;k<a.length;k++){  
//            if(a[k]%2==0){  
//               System.out.println(a[k]);  
//             }  
//           }  
//   }
// }  



// import java.util.*;
// class Main {
//   public static void main(String[] args) {
//     int[] arr = new int[5];
//     int even = 0;
//     int odd = 0;
//     int zero = 0;
//     for (int i = 0; i < arr.length; i++) {
//       Scanner sc = new Scanner(System.in);
//       System.out.println("Enter numbers you want to input in array :");
//       arr[i] = sc.nextInt();
//     }
//     for (int i = 0; i < arr.length; i++) {
//       System.out.print(arr[i]);
//     }
//     System.out.println();

//     for (int i = 0; i < arr.length; i++) {
//       if (arr[i] % 2 == 0) {
//         if (arr[i] > 0) {
//           even++;
//         } else if (arr[i] < 0) {
//           even++;
//         } else {
//           zero++;
//         }
//       } else if (arr[i] % 2 != 0) {
//         odd++;
//       }  else if (arr[i] == 0) {
//         zero++;
//       }
//     }
//     System.out.println("Even numbers :" + even);
//     System.out.println("Odd numbers :" + odd);
//     System.out.println("Zero numbers :" + zero);
//   }
// }





// import java.util.*;
//  class Main{  
//  public static void main(String args[]){  
//   System.out.print("Enter inputs number ");
//    Scanner s = new Scanner(System.in);
//         int x = s.nextInt();
//         int a[] = new int[x];
//         System.out.println("input numbers");
//         for(int i = 0; i < x; i++)
//         {
//             a[i] = s.nextInt();
//         }
//         System.out.println("Odd Numbers:");  
//        for(int j=0;j<a.length;j++){  
//           if(a[j]%2!=0){  
//               System.out.println(a[j]);  
//             }  
//           }  
//            System.out.println("Even Numbers:");  
//          for(int k=0;k<a.length;k++){  
//            if(a[k]%2==0){  
//               System.out.println(a[k]);  
//             }  
//           }  
//   }
// }  




import java.util.*;
class Main { 
    public static void main(String[] args) {  
       int[] arr = new int[5];
          for (int i = 0; i < arr.length; i++) {
            Scanner sc = new Scanner(System.in);
            System.out.println("Enter numbers you want to input in array :");
            arr[i] = sc.nextInt();
          }
      int i; 
      int max = arr[0];
      for (i = 1; i < arr.length; i++) 
          if (arr[i] > max) {
              max = arr[i]; 
        System.out.println("Maximum number in given array is " + max); }
         
       int min = arr[0];
      for (int j = 1; j < arr.length; j++){
          if (arr[j] < min) {
              min = arr[j]; 
        System.out.println("Minimum number in given array is " + min); }
      }
    
 } 
} 



// import java.util.*;
// class Main { 
//     public static void main(String[] args) {  
//        int[] arr = new int[5];
//           for (int i = 0; i < arr.length; i++) {
//             Scanner sc = new Scanner(System.in);
//             System.out.println("Enter numbers you want to input in array :");
//             arr[i] = sc.nextInt();
//           }
//       int i; 
//       int max = arr[0];
//       for (i = 1; i < arr.length; i++) 
//           if (arr[i] > max) {
//               max = arr[i]; 
//         System.out.println("Maximum number in given array is " + max); 
//             break;
//         }

//       }

//  } 
