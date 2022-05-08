package wordgame;

import java.util.Arrays;
import java.util.Scanner;

public class main {

	public static void main(String[] args) { 
     int totalPoint = 0;	
     String[][] words = new String[3][3];
     words[0][0] = "rose";
     words[0][1] = "army";
     words[0][2] = "coal";
     words[1][0] = "pizza";
     words[1][1] = "table";
     words[1][2] = "queen";
     words[2][0] = "island";
     words[2][1] = "breath";
     words[2][2] = "unique";
     
     Scanner scanner= new Scanner(System.in);
     int firstTour = random(2,0);
     String selectedWord1 = words[0][firstTour];
     if (firstTour==0) {
    	 System.out.println("A flower with a pleasant smell and thorns (= sharp points on the stem), that grows on a bush :");
     }
     else if (firstTour==1) {
    	 System.out.println("A military force that fights wars on the ground :");
     }
     else if (firstTour==2) {
    	 System.out.println("A hard, black substance that is dug from under the ground and burnt as fuel :");
     }	 
     System.out.println("Enter the answer 1 or request a letter 2");
     int choice = scanner.nextInt();
     if (choice==1) {
     String answer1 = scanner.next();
             if( answer1.toString().equals(selectedWord1)) {
 			
 			
 			 System.out.println("Correct! You gained 500 points.");
 			 totalPoint += 500;
 			
 	         }
 	         else if(!(answer1.toString().equals(selectedWord1)))
 	         {
 			
 			System.out.println("Wrong! You lost 500 points.");
 			totalPoint -=500;
 	         }
     }        
     else if (choice==2) {
    	 int letterNumber = random(3,0);
    	 char[] theWord = selectedWord1.toCharArray();
    			 
    	 char[] hintWord = {'*','*','*','*'};
    	 
    		hintWord[letterNumber] = theWord[letterNumber];
    		System.out.println(String.valueOf(hintWord));
    		System.out.println("Enter the answer 1 or request a letter 2");
    		int newChoice= scanner.nextInt();
    		int loop = 1;    		
    		while(loop<=4) {
    			int letterNumber2 = (int)(Math.random() * (3 + 1)) + 0;
    			    if (newChoice==2 && letterNumber==letterNumber2) {   			    	
    			    	continue;
    			    }
    			    else if(newChoice==1) {
    			    	break;
    			    }
    			    else {    			       			            			
    			    hintWord[letterNumber2] = theWord[letterNumber2];
    			    System.out.println(String.valueOf(hintWord));
    			    System.out.println("Enter the answer 1 or request a letter 2");
    			    newChoice = scanner.nextInt();
    			    loop++;
    			    } 
    				
    			}
    		if (loop>=4) {
    			System.out.println("There is no answer! You gained 0 point.");
    		}
    		else { 
    			System.out.println("Enter your answer : ");
    		    String answer1 = scanner.next();
    		    if( answer1.toString().equals(selectedWord1)) {
    		    	totalPoint += 400-(loop*100);
    		    	System.out.println("Correct! You gained " + (400-(loop*100)) + " points." );
    			 
    		    }
    		    else {
    		    	totalPoint -= 400-(loop*100);
    		        System.out.println("Wrong! You lost "+(400-(loop*100))+ " points." );}
    		         
    		       
    		    	
    		    
    		}
           }
    		 
     
     int secondTour = random(2,0);
     String selectedWord2 = words[1][secondTour];
     if (secondTour==0) {
    	 System.out.println("A food made from a flat, round piece of bread covered with cheese, vegetables, etc and cooked in an oven :");
     }
     else if (secondTour==1) {
    	 System.out.println("A piece of furniture with four legs, used for eating off, putting things on :");
     }
     else if (secondTour==2) {
    	 System.out.println("A female ruler in some countries :");
     }
     System.out.println("Enter the answer 1 or request a letter 2");
     int choice2 = scanner.nextInt();
     if (choice2==1) {
    	 String answer2 = scanner.next();
    	 	if( answer2.toString().equals(selectedWord2)) {
 			
 			
    	 		System.out.println("Correct! You gained 500 points.");
    	 		totalPoint += 500;
 			
    	 	}
    	 	else{
 	 
 			
 			System.out.println("Wrong! You lost 500 points.");
 			totalPoint -=500; 
    	 	}
    }
 	 
     else if (choice2==2) {
    	 int letterNumber = random(4,0);
    	 char[] theWord = selectedWord2.toCharArray();
    			 
    	 char[] hintWord = {'*','*','*','*','*'};
    	 
    		hintWord[letterNumber] = theWord[letterNumber];
    		System.out.println(String.valueOf(hintWord));
    		System.out.println("Enter the answer 1 or request a letter 2");
    		int newChoice= scanner.nextInt();
    		int loop = 1;    		
    		while(loop<=5) {
    			int letterNumber2 = (int)(Math.random() * (4 + 1)) + 0;
    			    if (newChoice==2 && letterNumber==letterNumber2) {   			    	
    			    	continue;
    			    }
    			    else if(newChoice==1) {
    			    	break;
    			    }
    			    else {   			       			            			
    			    hintWord[letterNumber2] = theWord[letterNumber2];
    			    System.out.println(String.valueOf(hintWord));
    			    System.out.println("Enter the answer 1 or request a letter 2");
    			    newChoice = scanner.nextInt();
    			    loop++;
    			    }
    				
    			}
    		if (loop>=5) {
    			System.out.println("There is no answer! You gained 0 point.");
    		}
    		else {
    			System.out.println("Enter your answer : ");
    		    String answer1 = scanner.next();
    		    if( answer1.toString().equals(selectedWord2)) {
    		    	totalPoint += 500-(loop*100);
    		    	System.out.println("Correct! You gained " + (500-(loop*100)) + " points." );
    			 
    		    }
    		    else {
    		    	totalPoint -= 500-(loop*100);
    		        System.out.println("Wrong! You lost "+(500-(loop*100))+ " points." );}
    		         
    		       
    		    	
    		}    
    		 
           }
     int thirdTour = random(2,0);
     String selectedWord3 = words[2][thirdTour];
     if (thirdTour==0) {
    	 System.out.println("an area of land that has water around it :");
     }
     else if (thirdTour==1) {
    	 System.out.println("the air that comes out of your lungs :");
     }
     else {
    	 System.out.println("different from everyone and everything else :");}
     System.out.println("Enter the answer 1 or request a letter 2");
     int choice3 = scanner.nextInt();
     if (choice3==1) {
     String answer3 = scanner.next();
     if( answer3.toString().equals(selectedWord3)) {
 			
 			
 			System.out.println("Correct! You gained 600 points.");
 			totalPoint += 600;
 			
 	 }
 	 else
 	 {
 			
 			System.out.println("Wrong! You lost 600 points.");
 			totalPoint -=600;
    	 
     }
     System.out.println("Your final point is : " + totalPoint);
	 } 
     else if (choice3==2) {
    	 int letterNumber = random(5,0);
    	 char[] theWord = selectedWord3.toCharArray();
    			 
    	 char[] hintWord = {'*','*','*','*','*','*'};
    	 
    		hintWord[letterNumber] = theWord[letterNumber];
    		System.out.println(String.valueOf(hintWord));
    		System.out.println("Enter the answer 1 or request a letter 2");
    		int newChoice= scanner.nextInt();
    		int loop = 1;    		
    		while(loop<=6) {
    			int letterNumber2 = (int)(Math.random() * (5 + 1)) + 0;
    			    if (newChoice==2 && letterNumber==letterNumber2) {   			    	
    			    	continue;
    			    }
    			    else if(newChoice==1) {
    			    	break;
    			    }
    			    else {   			       			            			
    			    hintWord[letterNumber2] = theWord[letterNumber2];
    			    System.out.println(String.valueOf(hintWord));
    			    System.out.println("Enter the answer 1 or request a letter 2");
    			    newChoice = scanner.nextInt();
    			    loop++;
    			    }
    				
    			}
    		if (loop>=6) {
    			System.out.println("There is no answer! You gained 0 point.");
    		}
    		else 
    			System.out.println("Enter your answer : ");
    		    String answer1 = scanner.next();
    		    if( answer1.toString().equals(selectedWord3)) {
    		    	totalPoint += 600-(loop*100);
    		    	System.out.println("Correct! You gained " + (600-(loop*100)) + " points." );
    			 
    		    }
    		    else {
    		    	totalPoint -= 500-(loop*100);
    		        System.out.println("Wrong! You lost "+(600-(loop*100))+ " points." );}
     }
     System.out.println("Your final point is " + totalPoint);
     }     	 					              						
	public static int random(int max, int min)	{	    		
	    int randomNum =(int)(Math.random() * ((max - min) + 1)) + min;
		return randomNum; 
		
	}
}
