# New-Project
This is my 1st new project

package Arrays;

public class AppearsOnce 
{
	public static void main(String[] args) 
	{
		int arr[]= {5,2,5,3,4,7,2,3,4};
		
		int res=arr[0];
		
		for(int i=1;i<arr.length;i++)
		{
			res=res^arr[i];
		}
		System.out.println("Single not repeated element is "+res);
		
	}

}

