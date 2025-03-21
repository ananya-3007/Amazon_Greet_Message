# Amazon_Greet_Message
def amazon_greet_message(if_buyer,name):
    print('Hello',name)
    if if_buyer:
        print('Welcome to BUYER Family')
        print('Whats on your Bucket List?')
    else:
        print('Welcome to VENDOR Family')
        print('What are you about to sell?')
amazon_greet_message(False,'Ananya')
    
