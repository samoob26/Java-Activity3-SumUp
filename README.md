# Java-Activity3-SumUp
Write a JAVA program that prompts the user for 5 integers

       int num1, num2, num3, num4, num5, sum, sum1, sum2, mult;

        System.out.print("1st num: ");
        num1 = input.nextInt();
        System.out.print("Input 2nd num: ");
        num2 = input.nextInt();
        System.out.print("Input 3rd num: ");
        num3 = input.nextInt();
        System.out.print("Input 4th num: ");
        num4 = input.nextInt();
        System.out.print("Input 5th num: ");
        num5 = input.nextInt();

calculates their sum & multiplies the first and last numbers

        sum = num1 + num2 + num3 + num4 + num5;
        sum1 = num4 - num3;
        sum2 = num1 + num5 * (num4 - num3) + num2;
        mult = num1 * num2;
    
applies a formula to the inputs before displaying the results.
     System.out.println("The sum of the 5 number is " + sum);
     System.out.println(num1+ " * " +num5+"="+mult);
     System.out.println(num1+" + "+num5+"("+num4+"-"+num3+")+"+num2+"="+sum2);
