public static string FizzBuzz(int number) 
{
	if(number % 3 == 0 && number % 5 == 0) 
	{
		return $"{number} : FIZZBUZZ";
	}
	else if(number % 3 == 0) 
	{
		return $"{number} : FIZZ";
	}
	else if(number % 5 == 0) 
	{
		return $"{number} : BUZZ";
	}
	else 
	{
		return $"{number} is not divisible by 3 or 5.";
	}
}