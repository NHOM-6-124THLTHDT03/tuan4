import java.util.Scanner;

public class BAI1 {
	public static void main(String[] args) {
		Scanner sc=new Scanner(System.in);
		System.out.println("Nhập số n trong dãy");
		int n=sc.nextInt();
		int S=0;
		for(int i=1;i<=n;i++)
		{
			S=S+i;
		}
		System.out.println(S);
	}
}
