import random

responses = [
    'Indisputably!',
    'Yes',
    'Try again',
    'Dont think about it',
    'No',
    'The prospects are very good'
]
#This is a greeting
print('Welcome to the fortune teller.')

#This is a request for a question
question = input('Ask your question:')

#This is a random answer selection
answer = random.choice(responses)

#Result
print(f'\nYour question: {question}')
print(f'Answer: {answer}')
