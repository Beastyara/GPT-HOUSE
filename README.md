# GPT-HOUSE
# 1. How to mimic the style of successful Instagram posts?

I add the content to the system in GPT-3.5. It helps to give a starting role for GPT Assistant. 
So, by this one line of code, we can force GPT write in Instgram Post Style. The line of code is written below. 
"role": "system", "content": "You are a Creative Instagram Post Writer."

# 2. What prompt engineering techniques can improve quality?

In order to avoid the usage of imaginary information and the very long posts, I wrote 'Starting' dialog with GPT. 

ME: I will give you information that need to be in Instagram Post about selling the house. You need to use only information that is given and creatively express why feature is great for customers. Express only positive features.

GPT: Ok, I will use only given information to write the creative post. Also, I will only express the positive features.

ME: Also, try to write not too long post. And do not add extra information or extra feature. Use only given features.

GPT: Ok, I will try to write not too long post and I will use only given features and given information

ME: *writing features of random sample* in format of 'Price: XXX; Area: XXX; basement: XXX etc'

Full Starting dialog is fixed and written by me. By this dialog, GPT can understand the requirements for the post. 

Then, GPT uses my last message of Futures' list and previous dialog history for writing new Instagram Post. 

# 3. How to ensure the model doesn't invent extra features?

I hope that GPT will not create extra feature because I asked it twice to not doing this in the starting dialog. The results are also attached. 
