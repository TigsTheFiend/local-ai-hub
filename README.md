I need to make sure anyone using this .pkg is aware of some things.

First, using this .pkg will do multiple things automatically (which is on purpose, as I wanted
the easiest setup experience for the average user).

Homebrew is the first thing to be downloaded and installed, and is used for installing, updating,
and managing software directly from the terminal. Homebrew is necessary to download and install
the second thing that is needed.

Python. Python is necessary to write and run code, build apps, things that are necessary in order
for this .pkg to work.

Second, and this is IMPORTANT. Using this .pkg will AUTOMATICALLY INSTALL APPLE MLX GLOBALLY. This
is not something to simply "skim over". Your Mac may warn you that installing MLX globally will
risk the core software of your M-series laptop. It is wrong. Apple's core software (which is needed
in order to restore and run MacOS) is protected on a READ-ONLY part of the drive. Your core software
IS protected, but if you do not feel comfortable with that information, you should not install this
.pkg, and go about your day.

Third, this .pkg will automatically set up four folders (and one run script) under your User folder.
You can find this folder by opening the application "Finder", going to the "Locations" section on the
sidebar (left side of Finder), and clicking on "Macintosh HD" (or if you have it showing, you can
just click straight to your user folder, where it has a house symbol, and your username), then click
on the folder "Users", then the folder with your username on it, and you will see three things that
may seem out of place.

You will see what looks like a white piece of paper (or something similar) that says "chatbot.py".
This is the chatbot's main code, which it will use inside your terminal to communicate with you
during your sessions using it. You will also see two folders that will be out of place. One folder
is named "saves", while another is named "personalities".

The saves folder is as it sounds. It is a folder of any saved sessions, so that you can continue
them later. The personalities folder has three sub-folders named "ai_roles", "user_roles", and
"world_settings". The two folders with "roles" in the name are for your personalities, and have your
character information inside of them (their height, weight, looks, history, relationships, the age
they live in (as in, modern age, medieval, what-have-you), etc.).
The world_settings folder is for your...well, world settings. This folder will have any created/
generated world settings/information that you create/generate with the AI. This includes time-periods
and information about the world your characters reside in.

Which brings me to the fourth thing that will happen automatically. This .pkg will download, and
install, an AI onto your system. This AI is referred to as "Llama", for those interested. Now, this
.pkg will set up a desktop application shortcut to run this command, and will tell your MacBook that
this file can be ran/trusted to run. Should you want a different image for the shortcut's icon. You
can change it. All you have to do is find the image you want (preferably a square one), and copy it..
Then you must right clickthe shortcut and click "get info". Now, this will open up a new Finder 
window that is small in size,and includes the name of your shortcut at the top. If you click on 
what looks like a white sheet ofpaper. You will see it become outlined in blue. This means it is
selected. Now, all you have to do is paste (Command+V), and it will be replaced. Now, when you
double click the .command file, it will open terminal, and start up the chatbot, which should bring
you to the main menu. Using the main menu is simple, use numbers and enter to make selections.

For example. It starts off by asking if you want to start a new scenario (1), browse and resume a 
story (2), or exit the hub (3). You want to start a new scenario? Just type 1, then hit enter. The
number 1 is going to be the default "go back" button, so that no matter the screen you're on (aside
from being in a chat), it will be the same button for going back a menu.

Now, you can create your own personalities without generating them. The AI will automatically create
the file and give it the correct layout if you generate it, but should you decide to create one
yourself. There are some things to consider to make things easier for the AI.

1) The AI personalities and User personalities are separate for a reason. This helps to keep the AI
from becoming confused like it might if they were within the same folder.
2) there is a correct layout to use, which I will show you an example of directly below. For the
purpose of understanding the layout, pretend the parenthesis aren't there. The parenthesis are
used to help you understand what information goes in that spot, or helps you understand what the
line is for should it not seem clear enough to me as I'm writing this. Also, if it goes to a second
line on here, it wouldn't when you write it in the .txt file. In that you would just hit "space"
instead of "enter".

[NAME]: (Character Name)\n[PHYSICAL BUILD]:6'0\" tall, 28B cup size.\n[CLOTHING PREFERENCE]:
Exclusively wears vibrant pink dresses.\n[PERSONALITY]: Extremely bubbly, deeply 
outgoing.\n[BACKSTORY & SECRETS]: Secretly terrified of spiders.\n[SPEECH QUIRKS]: Uses words like
\"Awesome!\" and \"Totally!\"

[YOUR NAME]: Alex\n[PERSONALITY]: A helpful classmate and close companion. (This is YOUR character's
relation to the AI's character should you wish to include it. You can leave it blank, or delete it)

[WORLD LOCATION]: Cozy Café\n[TIME PERIOD]: Modern Day\n[SUMMARY]: A warm local coffee shop on a
rainy afternoon."

That was an example, but feel free to change things around, or not include things (like world
information) if you don't want to, or if you want that information to be in the world settings file
instead.

Last thing, this .pkg (as far as I know of) only works on MacBooks with an m-series chip inside o it.
I have not tested, or checked, to see if it would work on anything else, or what changes would need
to be made in order FOR it to work. Hope this works well for anyone that tries it out and enjoy!
