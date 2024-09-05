# thoufii.code
package ytproject;

import java.util.Arrays;

public class bubblesort {

	/*	public static void main(String[] args) {
		int a[] = {64,34,25,12,22,11,90};
		System.out.println (Arrays. toString(a));
		for (int i=0;i<a.length-1;i++)
		{
		for (int j=0;j<a.length-1-i;j++)
		{
		if(a[j]>a[j+1])
		{
		int t=a[j];
		a[j] = a[j+1];
		a[j+1]=t;
		}
		}
		}
		System.out.println (Arrays.toString(a));
		}
}*/



    public static void main(String[] args) {
        int[] rock = {1, 2, 3, 4, 5};
        
        // Reverse the array
        for (int i = 0; i < rock.length / 2; i++) {
            int temp = rock[i];
            rock[i] = rock[rock.length - 1 - i];
            rock[rock.length - 1 - i] = temp;
        }
        
        // Print the reversed array
        System.out.println(Arrays.toString(rock));
    }
}



