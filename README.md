# First-rep

#This is my pre-work chat bot

def chatbot():
  print("Hello! My name is Chad. Possible responses include: \n Hey \n Hello \n Hi\n")
  
  while True:
    user_response = input()
    
    if user_response == "Hi" or user_response == "Hello" or user_response == "Hey" or user_response == "No, let's keep talking":
      print("\nHow are you? Possible responses include: \n Good \n I'm okay\n")
      
    elif user_response == "Good" or user_response == "I'm okay":
      print("\nAwsome! Would you like to ask me a question? Possible responses include: \n Yes \n No\n")
      
    elif user_response == "Yes":
      print("\nWhay would you like to ask? Possible responses include: \n How old are you? \n Where are you from\n")
      
    elif user_response == "Where are you from":
      print("\nI am from Austin texas. Would you like to end this conversation now? Possible responses include: \n Yes, I would like to end this conversation \n No, let's keep talking\n")
      
    elif user_response == "How old are you":
      print("\nI am 200 years old. Would you like to end this conversation now? Possible responses include: \n Yes, I would like to end this conversation \n No, let's keep talking\n")
 
    elif user_response == "No" or user_response == "Yes, I would like to end this conversation":
      print("Okay, goodbye.")
      break
      
    else:
      print(" I don't understand your response, make sure to only use responses from the provided options.")

chatbot()
