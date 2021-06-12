# Magic 8-Ball

The **Magic 8-Ball** is a plastic sphere, made to look like an eight-ball, that is used for fortune-telling or seeking advice. The user asks a question to the ball, then turns it over to reveal an answer in a window on the ball. In this project, the user can ask any question through a microphone and the magic 8-ball works its magic to reveal the fortune of the user ;)

![image](https://user-images.githubusercontent.com/85028192/121771693-81e51280-cb8e-11eb-9051-0edb69ce9a2f.png)

## Components Required

1. Arduino
2. Batteries
3. HC-05 Bluetooth Module
4. LCD Display
5. A plastic Magic 8-ball
6. A smartphone with Andriod App

## Voice Recognition Technology

Voice or speaker recognition is the ability of a machine or program to receive and interpret dictation or to understand and carry out spoken commands. Voice recognition has gained prominence and use with the rise of AI and intelligent assistants, such as Amazon's Alexa, Apple's Siri, Google Home and Microsoft's Cortana.

Voice recognition software converts analog audio into digital signals, known as analog-to-digital conversion. For a computer to decipher a signal, it must have a digital database, or vocabulary, of words or syllables, as well as a speedy means for comparing this data to signals. The speech patterns are stored on the hard drive and loaded into memory when the program is run. A comparator checks these stored patterns against the converted digital signals - an action called pattern recognition. Simply put, by using machine learning and sophisticated algorithms, voice recognition technology can quickly turn your spoken words into written text.

## The App

Android speech-recognition app, which we will be using for this project, was developed using MIT App Inventor. When the app is running in the smartphone, user’s voice commands are detected by the microphone present in the phone. Commands are processed, and speech-to-text conversion is done within the app using Google’s speech-recognition technology.

![image](https://user-images.githubusercontent.com/85028192/121771700-945f4c00-cb8e-11eb-8e14-148073e63101.png)

The text is transferred to other devices via bluetooth. The phone needs to be paired with other bluetooth devices for the transfer.

## The Project

The smart phone is first paired with the HC-05 Bluetooth module installed in the ball. The user starts by speaking of his question by switching ON the mic in the app. Then the app converts the speech into text and transmits the data to the ball. The data is now transferred to the microcontroller which activates the program and LCD Display. A random answer is generated on the LCD Display. <br />
That's it! Our Magic 8-Ball is ready to reveal our fortune.

## Python code for Magic 8-ball

Here is a simple code. We can add more responses to the ball.

``` python
#Make a Magic 8 ball

import random
answers = ['It is certain', 'It is decidedly so', 'Without a doubt', 'Yes – definitely', 'You may rely on it', 'As I see it, yes',
'Most likely', 'Outlook good', 'Yes Signs point to yes', 'Reply hazy', 'try again', 'Ask again later', 'Better not tell you now',
'Cannot predict now', 'Concentrate and ask again', 'Dont count on it', 'My reply is no', 'My sources say no',
'Outlook not so good', 'Very doubtful']

print('  __  __          _____ _____ _____    ___  ')
print(' |  \/  |   /\   / ____|_   _/ ____|  / _ \ ')
print(' | \  / |  /  \ | |  __  | || |      | (_) |')
print(' | |\/| | / /\ \| | |_ | | || |       > _ < ')
print(' | |  | |/ ____ \ |__| |_| || |____  | (_) |')
print(' |_|  |_/_/    \_\_____|_____\_____|  \___/ ')
print('')
print('')
print('')
print('Hello World, I am the Magic 8 Ball, What is your name?')
name = input()
print('hello ' + name)


def Magic8Ball():
    print('Ask me a question.')
    input()
    print (answers[random.randint(0, len(answers)-1)] )
    print('I hope that helped!')
    Replay()
    

def Replay():
    print ('Do you have another question? [Y/N] ')
    reply = input()
    if reply == 'Y':
        Magic8Ball()
    elif reply == 'N':
        exit()
    else:
        print('I apologies, I did not catch that. Please repeat.')
        Replay()

		
Magic8Ball()

```
