## How it started? ##
  All started when fans of both AK and VJ wanted to know which film made the more collection. This project was created for fun and I wanted to make a project that be keep me hooked the theme.
  
## About the project ##
This projects allows the user to know about the collection of a movie in a particular day and Data is collected from paytm movies. So, You can expect BMS data here. I will try to add BMS later. This project do not have any GUI. It uses CLI for Interaction.

## How it works? ##

- Install all packages required for this project from ````requirements.txt````.
- Run the python file and you will be prompted for 2 inputs.
- First input will prompt you to enter for movie. For now it asks for varisu and thunivu but if you are not looking for this movies. you can also enter other movie names.
- ````Path 1:```` if you choose varisu or thunivu. It will move to next input.
- ````Path 2:```` if you enter other movie then it will prompt you to enter movie code. So how to know the movie code. Go to the movie page in paytm website and you will see url like this in address bar : https://paytm.com/movies/thunivu-movie-detail-156586?````frmtid=o_7tzoqjs````. The frmtid is your movie code. Soon I will try to automate this.
- Second input will prompt you to enter the current date or future date in particular format. Please don't enter less than current date it will automatically take current date.
- It take sometime to calculate the collection and You will receive areawise collection information in excel.
