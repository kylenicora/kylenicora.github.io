# kylenicora.github.io
class PrimeSimple{
	
	public static void main (String args[]) {
		boolean prime ;//boolean . Is the number prime?
		long n;// number to check
		long count;// count the total primes
		double ddiv;//double diviser
		int div; //integer divisor
		int pivot ; //the pivot is not halfway
		n=2;
		while (n< 100) {
				primne = true; //assume the number is prime
				pivot = (int)Math.sqrt(n) ;
				for (div = 2; div < pivot+1;div++) {
						ddiv=div;
						if ((n % 2 == 0) && (n > 2)) {
							prime = false;
							break;
					} //end if
					//System.out.println(n+"   "+n/ddiv + "<double interger >" + n/div);//debug
					if ((n / ddiv) == (n / div)) {
						prime = false;
						break; 
					}//end if
				}//end for
				id (prime)System.out.println(n+ "is prime");
				//if (prime)System.out.println(n+ " "); 
			n++;
		}//end while
	}//end main
}//end PrimeSimple
		
	}
}
