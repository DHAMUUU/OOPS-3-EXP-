# OOPS-3-EXP-
1.
import java.util.*;
public class Question_2 
{
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter a String");
        String str = sc.nextLine();
        char firstChar = str.charAt(0); 
        String strne=firstChar+str.substring(1).replace(firstChar, '$');
        System.out.println("Output:");
        System.out.println(strne); 
    }
}

2.import java.util.*;
public class Question_5 
{
    public static void main(String[] args) 
    {
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter the Sentence");
        String str=sc.nextLine().trim();
        String arr[]=str.split(" ");
        System.out.println("Enter the word to search");
        String sr=sc.next();
        int count=0;
        for(int i=0;i<arr.length;i++)
        {
            if(arr[i].equals(sr))
            {
                count++;
            }
        }
        System.out.println("The Given word "+ sr+ " is found "+count+" times");
    }
}


