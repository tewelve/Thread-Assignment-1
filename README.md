# Thread-Assignment-1

import java.util.ArrayList;

public class Iterator
{
	 public static void main(String a[]){
	        ArrayList<String> arrl = new ArrayList<String>();
	        //adding elements to the end
	        arrl.add("First");
	        arrl.add("Second");
	        arrl.add("Third");
	        arrl.add("Random");
	        java.util.Iterator<String> itr = arrl.iterator();
	        while(itr.hasNext()){
	            System.out.println(itr.next());
	        }
	    }
	}

