# RGN-Discord-Bot
Jasmine:
I researched some resources for the python and javascript library. Bk and I do not have much experience with either. We came to the conclusion Python may be the easiest for beginners.
We found the discord.py documentation. I shared this with BK and he followed the tutorial on this for the beginner hello bot. Link to tutorial: https://discordpy.readthedocs.io/en/latest/quickstart.html
I followed a similar tutorial from youtube for my a personal discord server: https://www.youtube.com/watch?v=cCiqcu2NP8I&list=PL-7Dfw57ZZVRB4N7VWPjmT0Q-2FIMNBMP&ab_channel=JamesS

Ethan 1: Using the resources Jasmin provided, I made a mock bot to get a feel for how it works. To do so, I made a new bot in the discord applications menu and had to tune what permissions the bot needed like being able to read messages. After making the bot settings, I then invited it to the discord server being used for the project. I then followed a guide for a simple bot, which I ran into the issue of actually getting it to work for a bit. After realizing I goofily forgot to put in the token for the bot into the program, I got it to work with basic "Hello" responses. 

Jasmine: I'm having a lot of trouble forking the github and getting my code onto the forked branched. I have googled commands and am trying to pull and then push, however I haven't worked with branches much. 

Ethan 2: Bad manners probably for doing all this is one giant commit, but just worked with and submitted the ability for the bot to interact and grant a user roles, with the ability to also take those roles away if the user so chooses. The bot can respond with both the name of the role or an emoji associated with it (which the bot details in its initial message. The bot should message someone on joining the server and through a manual call using '!roles' in the server. Initially, there was an issue where the bot kept returning the in built exception, and the console was giving an error that stated "'NoneType' object has no attribute 'id'". I looked up this error and recieved a lot of information, though none worked. What I then realized was that because I had made the roles in the server have an uppercase first letter when it was basically looking for all lowercase. Once I made all the roles lowercase it completely fixed the issue and I ran into no other issues. I added the ability for the bot to take away roles after that, and voila: this segment was done.
