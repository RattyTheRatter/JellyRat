# JellyRat
New Github cause old one got term

# Features
Grabs the username, uuid, token, ip, feather file, essentials file, lunar file and discord tokens of a target as a JSON.

Apparently switching the feather or essential files with yours grants you infinite access to their account thanks to the refreshToken. (Unconfirmed, ask Annah#5795)

Additionally, it stores a formatted session string ready to use with Token login mods 

Discord injection so when they reset there password you get the token again

JavaScript backend server which:

Checks if all fields in the JSON are present.
Controls requests and filters out spam requests by IPs.
Validates the token with Minecraft Auth servers before proceeding to output the data.
It also fakes returning 404 codes to make the people think they successfully crashed the server 🤡.

Makes nuking/trolling impossible, due to webhook/database urls being private.

Can be easily configured to either use Discord Webhooks or MongoDB or both.

Bypasses PizzaClient's SessionProtection.

Steals microsoft email and password and there refresh token

Great New Look

https://raw.githubusercontent.com/RattyTheRatter/JellyRat/main/Ratting_Methods.txt for ratting methods



# Disclaimer
This is for educational purposes only. I am not responsible for any damage caused by this tool.
