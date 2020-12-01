![Octocat picture](https://github.com/Gamerize/Task-1/blob/main/download.png)
# Issac Wai

## Breakfast

Yesterday, I had some bacon and french toast for breakfast.

## LinkedIn Account

[linkedIn](https://www.linkedin.com/in/wai-issac-27858b1ba/)

## My top 5 games

1. Super Smash Bros Ultimate

2. Monster Hunter World

3. Monster Hunter Generations Unltimate

4. Mario Kart Wii

5. Sonic Generations

## Checklist for Pro Dev

- [ ] Report

- [x] LinkedIn 

- [ ] Website

## Code from GEC

	do
	{
		do
		{
			cout << "Please enter a number (1 to 10): ";
			cin >> num1;
			if (num1 > 10 || num1 < 1)
			{
				cout << "Invalid number, please re-enter." << endl;
			}
		} while (num1 > 10 || num1 < 1);

		for (int i = 0; i < num1; i++)
		{
			for (int j = 0; j < i; j++)
			{
				cout << "*";
			}
			cout << endl;
		}

		cout << "Do you wish to have another go [Y or N]?: ";
		cin >> ans;
		if (ans == 'n' || ans == 'N')
		{
			cout << "Goodbye!" << endl;
		}
	} while (ans == 'y' || ans == 'Y');
	

	return 0;

