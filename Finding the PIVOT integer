/***Find the Pivot Integer***/
/*Example 1:

Input: n = 8
Output: 6
Explanation: 6 is the pivot integer since: 1 + 2 + 3 + 4 + 5 + 6 = 6 + 7 + 8 = 21.

Example 2:

Input: n = 1
Output: 1
Explanation: 1 is the pivot integer since: 1 = 1.

Example 3:

Input: n = 4
Output: -1
Explanation: It can be proved that no such integer exist.
*/


using System;
					
public class Program
{
	public static void Main()
	{
		int result = PivotInteger(8);
		Console.WriteLine(result);	
	}
	 public static int PivotInteger(int n) {
        // // If pivot * pivot is equal to sum (pivot found) return pivot, else return -1
        int sum = (n*(n+1)/2);
        int pivot = Convert.ToInt32(Math.Sqrt(sum));
        return pivot * pivot == sum ? pivot : -1;
    }
}
