1. Explain what frame-work/technologies you used
I created a command-line app using python langauge. I was about to continue the project using Typer library.
2. How to run the project
Upload the .ipynb file to Google Colab and run the code.
3. What remote Database hosting service you are using 
I was trying to use XAMPP and PHPmyAdmin but failed to login to PHPmyAdmin.
4. Commands to navigate through ( if you have a  command-line application)
the commands and instructions are printed at the beginning when we run the code.

1. Explain what frame-work/technologies you used
	I created a command-line app using python langauge with libraries _mysql from MySQLdb, argparse, and pandas.
	Also, getshell is used from google_colab_shell to have a terminal interface in Google Colab.
2. How to run the project
	a. upload the test.py as a notebook to Google Colab.
	b. run the cell to start terminal interface. ($ colab >>)
	c. in the files tab to the left of google colab, upload the test.py file so that when we run the command ls in the terminal, we can see file test.py listed.
	d. double click on the file and it will be opened to the right of google colab's window.
	e. remove the two !pip lines from the content of text.py file.
	f. run the example commands found at the file one by one in the terminal and notice the change (if any) in the database.
3. What remote Database hosting service you are using 
	I used www.db4free.net and phpMyAdmin to host my remote database there.
	With username melzahar, password 12345678, and database name prem_league_db.

4. Commands to navigate through ( if you have a  command-line application)
Here are examples of the commands used (also found as comments at the end of the test.py file).

# Add a new user review on a match
#python test.py -r -n melzahar2 -s "Old Trafford, Manchester" -d 2022-05-02 -t 4 -w good

# View existing reviews on a given match
#python test.py -v -s "Old Trafford, Manchester" -d 2022-05-02

# Register a user
#python test.py -u -e melzahar@aucegypt.edu -n mennaz -g f -b 2000-02-16 -f "Manchester United"

#python test.py --Get_player_info "Adam Lallana"
#python test.py --Get_team_info Brentford
#python test.py --Get_players_by_nationality England
#python test.py --Get_players_by_position Forward
#python test.py --Get_HomeTeam_of_stadium "Emirates Stadium"

#python test.py --Get_top10_by_HomeMatches
#python test.py --Get_top10_by_Matches
#python test.py --Get_top10_by_YellowCards
#python test.py --Get_top10_by_fouls
#python test.py --Get_top10_by_shots

#python test.py --Get_top_team_of_season 2018/2019