# Lesson6
# Homework
Write a program that works out if a number is odd or even

		int main() {
		int n;

		cout << "Enter a number:\n";
		cin >> n;

		if (n % 2 == 0)
		cout << n << " is even.";
		else
		cout << n << " is odd.";

		return 0;

Write a program to check whether a number is positive, negative or zero.


		#include <iostream>

		using namespace std;
		int main()
		{
		int num;
		cout << "Enter the number" << endl;
		cin >> num;
		if (num > 0) {
		}
		else if (num < 0) {
		cout << num << " is a negative number";
		}
		else {
		cout << "You entered Zero";
		}
		return 0;
		}

Write a program to calculate profit or loss. The program should ask the user  for the purchase price and sale price then calculate whether profit or loss was  made on the sale.


		# include <iostream>
		using namespace std;
		int main()
		{
			int pp, sp, profit, loss;
			cout << "Enter Purchase Price:" << endl;
			cin >> pp;
			cout << "Enter Sale price:" << endl;
			cin >> sp;
			if (sp > pp)
			{
				profit = sp - pp;
				cout << "profit" << profit << endl;
			}
			else if (pp > sp)
			{
				loss = pp - sp;
				cout << "Loss of " << loss << endl;
			}
			else
			{
				cout << "No Profit no Loss.";
			}
		}

Name a shape

		#include <iostream>
			using namespace std;
			int main()
		{
			int shapeSides;
			cout << "How many sides does the shape have?\n" << endl;
			cin >> shapeSides;

			if (shapeSides == 3)
				{
					cout << "The shape is a triangle\n" << endl;
				}
				else if (shapeSides == 4)
				{
					cout << "The shape is a square\n" << endl;
				}
				else if (shapeSides == 5)
				{
					cout << "The shape is a pentagon\n" << endl;
				}
				else if (shapeSides == 6)
				{
					cout << "The shape is a hectagon\n" << endl;
				}
				else if (shapeSides == 7)
				{
					cout << "The shape is a heptagon\n" << endl;
				}
				else if (shapeSides == 8)
				{
					cout << "The shape is a octagon\n" << endl;
				}
				else if (shapeSides == 9)
				{
					cout << "The shape is a nonagon\n" << endl;
				}
				else if (shapeSides == 10)
				{
					cout << "The shape is a decagon\n" << endl;
				}
				else
				{
					cout << "The shape is not identified\n" << endl;
				}
		}

Vote

	#include <iostream>
	using namespace std;

	int main()
	{
	    cout << "Kindly enter your age to see whether you can vote or not!\n";
	    int age;
	    cin >> age;
	    if(age>=18)
	    {
		cout << "You can vote";

	    }
	    else
	    {
		cout << "Sorry not today";
	    }

	}
	
Good morning

	#include<iostream>
	using namespace std;
	int main()
	{
		cout << "Enter the time in 24 hour pattern to see whether it Morning, Afternoon, Evening or Night\n";
		double time;
		cin >> time;
		if (time < 12)
		{
			cout << "Good Morning";
		}
		else if (time >= 12 && time < 18)
		{
			cout << "Good Afternoon";
			}
		else if (time >=18 && time < 21)
		{
			cout << "Good Evening";
		}
		else if (time >=21 && time <24)
		{
			cout << "Good Night";
		}
		else
		{
			cout << "Incorrect input";
		}
	}
