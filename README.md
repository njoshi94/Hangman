Hangman Instructions and Documentation:

Hello! Welcome to my Hangman Game utilizing Machine Learning and AWS

The download link for the exe file can be found here: https://tinyurl.com/ybmgvltr

Below are notes regarding the game:

HardMode: 
	Enabling this mode will pull words from a website generating strange and unusual words 
	The current word library includes some difficult words, but also many common words 

Online Mode:
	Enabled: All data will be pulled from and stored on DynamoDB on AWS. No additional file required 
	Disabled: All data will be stored locally. Words file needed. Machine Learning file will be 
		automatically created if one does not exist. 'ML1.xlxs' can be used as a starting point if preferred

Textbox commands:
	Entering 'list' will display words already guessed
	Entering 'quit' will automatically end the game 
