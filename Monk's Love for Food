	import java.io.BufferedReader;
	import java.io.InputStreamReader;
	import java.util.Stack;
	
	
	public class Stacks
	{
		public static void main(String args[])throws Exception
		{
			BufferedReader s =new BufferedReader(new InputStreamReader(System.in));
			int q=Integer.parseInt(s.readLine());
			Stack<Integer> st=new Stack<Integer>();
			for(int i=0;i<q;i++)
			{
				String inp[]=s.readLine().split(" ");
				if(Integer.parseInt(inp[0])==1)
				{
					if(!st.isEmpty())
					{
						System.out.println(st.peek());
						st.pop();
					}
					else
						System.out.println("No Food");
				}
				else
					st.push(Integer.parseInt(inp[1]));
			}
		}
	}
