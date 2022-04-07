#Ask the user if it is raining and convert their answer to lower case so it doesn't matter what case they type it in. If they answer "yes" ask if it is windy. If they answer "yes" to this second question, display the answer "It is too windy for an umbrella", otherwise display the message "Take an umbrella". If they did not answer yes to the first question, display the answer "Enjoy your day"


Raining =input('Is it raining? (yes/no)')
ans1 =Raining.lower()
if ans1 =='yes':
  windy =input('Is it windy? (yes/no)')
  ans2 =windy.lower()
  if ans2 =='yes':
    print('It is too windy for an umbrella')
  elif ans2 =='no':
    print('Take an umbrella')
  elif ans1 =='no':
      print('Enjoy your day.') 
