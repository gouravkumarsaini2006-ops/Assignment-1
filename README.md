Q1. Explain the difference between the following data types with examples:
Integer (int)
An integer is simply a whole number — no decimal, no fraction. It can be positive, negative, or zero.
For example, if Gourav counts his daily steps, he'd write steps = 8500. Or if he went down to a basement, floors_climbed = -2.
Float (float)
A float is a number with a decimal point. We use it when we need more precision.
For example, Gourav's running distance might be distance_km = 5.75 or his body temperature could be temperature = 98.6.
String (str)
A string is just text. We write it inside single or double quotes. Even a number written inside quotes becomes a string.
For example, user_name = "Gourav" or postal_code = '302001'.
Boolean (bool)
A boolean has only two possible values — True or False. Think of it like a light switch, either on or off.
For example, is_gourav_logged_in = True or has_passed_exam = False.

Q4. Explain any five commonly used string methods in Python with examples.
upper()
This method converts all the letters in a string to capital letters.
pythonmessage = "victory"
print(message.upper())  # Output: VICTORY
lower()
This is the opposite of upper(). It turns all letters into small letters.
pythonplayer = "GOURAV"
print(player.lower())  # Output: gourav
strip()
This removes extra spaces from the beginning and end of a string. Very useful when users accidentally add spaces while typing.
pythondirty_input = "   username123   "
print(dirty_input.strip())  # Output: username123
replace()
This finds a word or letter in a string and replaces it with something else.
pythonsentence = "Gourav loves android apps."
print(sentence.replace("android", "ios"))  # Output: Gourav loves ios apps.
find()
This searches for a character or word inside a string and tells you its position. Positions start from 0. If it's not found, it returns -1.
pythonword = "laptop"
print(word.find("p"))  # Output: 2

Q7. What is Artificial Intelligence (AI)? Explain its importance and mention any four real-life applications of AI.
Definition
Artificial Intelligence, or AI, is a part of computer science where we build machines and programs that can think and work like humans. These systems can learn from data, find patterns, and make decisions on their own.
Importance
AI is important because it can process huge amounts of data very quickly — something humans simply can't do. It doesn't get tired, doesn't make careless mistakes, and can work 24 hours a day. It helps doctors, scientists, and businesses make better decisions.
Four Real-Life Applications
1. Healthcare
AI can look at X-rays and MRI scans and detect diseases early, sometimes even faster than doctors.
2. Streaming Platforms like Spotify and YouTube
These apps watch what you listen to or watch, and then suggest new songs or videos that match your taste.
3. Navigation Apps like Google Maps
AI checks live traffic, accidents, and road blocks, and finds the fastest route for you while you're driving.
4. Bank Fraud Detection
If Gourav suddenly makes an expensive purchase in another country, the bank's AI immediately notices something unusual and flags it to stop theft.

Q8. Identify whether the following are examples of AI and explain why:
ChatGPT — Yes, it is AI.
ChatGPT reads what you type, understands the meaning, and gives a fresh answer every time. It doesn't just pick from a ready-made list — it actually thinks and forms a response.
Google Maps Route Prediction — Yes, it is AI.
Google Maps doesn't just show a fixed road. It keeps checking real-time traffic, past patterns, and even weather to suggest the best route at that moment.
Calculator — No, it is not AI.
A calculator just follows fixed rules. It can't learn anything new or think on its own. Every time Gourav presses equals, it simply runs the same math formula.
Netflix Recommendations — Yes, it is AI.
Netflix studies your watch history, compares it with other users, and suggests shows it thinks you'll enjoy. That's machine learning at work.
Voice Assistants like Alexa and Siri — Yes, they are AI.
They listen to your voice, understand what you're asking, and then take action. They can even understand different accents, which shows real intelligence.
