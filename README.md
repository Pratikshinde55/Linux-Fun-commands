# Linux-Fun-commands
"Exploring the Fun Side of Linux: A Journey Through Entertaining Terminal Commands" 

![image](https://github.com/Pratikshinde55/Linux-Fun-commands/assets/145910708/f6ed21dc-3f30-46b7-8089-5a4155273c6f)


Install Required Packages:

If any of the fun commands are not already installed on our Amazon Linux instance, we can use the package manager yum to install them. For example,
to install cowsay, we can use:

      # yum install cowsay

⚡To run cowsay with a custom message:

      #cowsay "hey Good moring today is 4 april"

![Screenshot 2024-04-04 150736](https://github.com/Pratikshinde55/Linux-Fun-commands/assets/145910708/db5be2df-1a65-474e-9f4b-fa9c2ca25f3d)

⚡To display a rainbow-colored text:

for this need install package:lolcat: Since lolcat is a Ruby gem, we can install it via RubyGems:
      
      #sudo yum install ruby
      #sudo gem install lolcat

command:

     #echo "Hi, I am pratik shinde from DevOps world !!!"  | lolcat

![Screenshot 2024-04-04 151601](https://github.com/Pratikshinde55/Linux-Fun-commands/assets/145910708/a2255471-bedb-454d-9428-9852dbd384cd)

      
⚡cowsay -f stegosaurus: Displays a stegosaurus instead of a cow:

     #cowsay -f stegosaurus "Hello,i am ps !"

![Screenshot 2024-04-04 152849](https://github.com/Pratikshinde55/Linux-Fun-commands/assets/145910708/1444e7cd-e359-44f6-af10-dcf4fdb35058)

⚡yes: Prints a continuous stream of "y" or any other specified string:

    # yes "hey I am Pratik !"

![linux-fun](https://github.com/Pratikshinde55/Linux-Fun-commands/assets/145910708/48a9299b-3db7-4efe-a1f1-a064da1559d3)


⚡rev: Reverses lines character-wise.

    #echo "HI, Pratik !" | rev

![linux-fun2](https://github.com/Pratikshinde55/Linux-Fun-commands/assets/145910708/31d85e3f-37cb-4a8f-a4f8-66a39ad83ed1)


⚡cowsay -l: Lists all available cow files (ASCII art):

    #cowsay -l

command:

    #cowsay -f dragon "hi i am dragon"

![linux-fun-3](https://github.com/Pratikshinde55/Linux-Fun-commands/assets/145910708/3f578534-336d-46eb-bf3e-9cd52b8fc595)

⚡fortune, which displays a random, hopefully interesting, adage or fortune:

    #sudo yum install fortune-mod
    #fortune

⚡figlet to generate ASCII art from text:

    #sudo yum install figlet
    #figlet "Hello, world!"


⚡The sl command is a fun utility that displays a steam locomotive animation in your terminal. It's a humorous take on the common mistype of sl instead of ls:

    # sudo apt install sl
    # sl
    # sl -F


⚡ cmatrix: Add the Matrix effect:

    #sudo apt install cmatrix
    #cmatrix


⚡ xeyes: eye watching 

   #sudo apt install x11-apps
   #xeyes


















     




