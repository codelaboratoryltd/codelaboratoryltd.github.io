## How to get started with Software Development 
the first step that will be required of you when starting out is to get an email address created or set up in order to receive and send relevant information and invites to other developers.
To do this you would need to firstly access your personal email account and enable the 2-factor authentication factor as well as verify the email address is both able to receive and send mail, the way in which we do this is by using a tool called ismyemailworking 
[click here](http://ismyemailworking.com/)
to create the forwarding address using Gmail you will need to log in to the destination address and open the accounts tab in the settings menu from here the next step is to click the add another address in to send mail as section and thn untick the treat as alias box that comes up, you will then need to use the correct server type and the password that is generated for the new address to finish setting up the business email forwarder. it is at this point that the ismyemail working tool will be used.

if you need a more in depth step by step explanation on this process then click the guide link to take you to a website that will guide you through the process step my step in more detail.
[guide](https://forwardemail.net/en/faq#how-to-send-mail-as-using-gmail
)


## Tools needed for initial development

after setting up the business email explained in the previous section the next step is to get your work machine up to date with all the required software versions and tools.
these are the tools needed from the get go:

## homebrew 
Homebrew is used to install the other tools in a bash window as well as used to update certain aspects. this software can be downloaded off of Google Chrome by using the following link [homebrew](https://brew.sh/) after down you copy the code on the website you will then need to open up the standard terminal that comes on your chosen software and paste the line into the terminal to install the program.

## iterm2
iterm 2 is an upgraded terminal that can be installed and used instead of the preset as it has a much nicer and easier to understand interface to download this new terminal follow the link to the website and download the version that is newest or that runs best on your machines specifications [iterm2](https://iterm2.com/downloads.html)

## GitHub
GitHub is what is known as a vcs or version control software it is used by the developers in a business to access the same files and edit sections without it affecting the other developers actions even though it is the same file it creates separate branches, think of these like a parallel universe as everything is the same however if one changes there is no affect to the other branches of the software. to join the git hub for your business you will need to be sent an invitation by a member of the organisation.[GitHub](https://github.com/)

## slack
Slack is a software similar to GitHub in the fact that it is used within an organisation however the varying factor is that slack is only used to communicate via text channels as well as audio and video calls. to install slack it is similar to GitHub as it is downloaded from chrome and then an account is created, before you are able to communicate with the other members of the organisation you must receive an invitation just like is the case when first installing GitHub after this the software is easy to use and is very efficient at allowing multiple members to communicate at the same time in different text channels or servers.[Slack](https://slack.com/intl/en-gb/) 

## golang
golang is a type of programming language that is used by many types of developers for creating the software as it is a much easier and smoother language to use than some other available languages not only this, but it also has a much faster run and compile time when compared to other similar types of languages. it is also a lot easier to learn to use than other available languages making it a great choice for someone who is just starting out in this industry. the installation for goland is fairly simple it is downloaded off of chrome and the file is then opened up and installed onto the machine in the case of a MAC it is dragged into the application's folder. once the program is open and running you can link it to your GitHub account as this allows the programmer to access the different URLs they are currently working on whilst inside the goland window allowing a much more convenient method of opening and finding required files.[goland](https://www.jetbrains.com/go/promo/?source=google&medium=cpc&campaign=10165081599&gclid=CjwKCAjwy7CKBhBMEiwA0Eb7ajtsjeN8VB1aZAl00Xbf3ypifKKEil0FfV_MOqd8Xy_x1gWWpnQNmBoCiesQAvD_BwE) a good website to learn the basics of goland is [tutorial](https://www.w3schools.com/go/index.php) as it offers a well explained tutorial as well as opportunities to test out the different functions and factors explained throughout as well as small exercises to help you learn by doing practical and theoretical training.
(![img_4.png](img_4.png) 

## Overview of  a ssh key 
A ssh key is a pair of files one that is private and one that is public that are used as a type of password to gain access to important files, because of this it is very important to generate and store a ssh key when working on any project.It is also needed to be attached to your GitHub account as without it, you will not be able to create repositories or use push or pull requests as it will not know where the commands are coming from, this is because a ssh key is not just a password but also acts as a form o id for the machine it was generated from.

### generating a ssh key 
To generate a ssh key a terminal is used on the machine you are using so the first step is to open up iterm2 and in the command line you will use the code: ssh-keygen -t rsa. Once this command has been run it will ask you where you would like to store the key as well as a passphrase to name it however if you leave them blank by just pressing the enter key then it will use the default locations for your machine. If the command has been successful it will create a pair of files one being the public key and one being the private key. the terminal will look something like this,Your identification has been saved in /Users/myname/.ssh/id_rsa.

Your public key has been saved in /Users/myname/.ssh/id_rsa.pub.
The key fingerprint is:
ae:89:72:0b:85:da:5a:f4:7c:1f:c2:43:fd:c6:44:38 myname@mymac.local
The key's randomart image is:
+--[ RSA 2048]----+
|                 |
|         .       |
|        E .      |
|   .   . o       |
|  o . . S .      |
| + + o . +       |
|. + o = o +      |
| o...o * o       |
|.  oo.o .        |
+-----------------+

After this has been done the private key will be stored in the id_rsa file in the .ssh directory and will be used to verify the public key that is used by the same computer. however, the public ke will be stored in a different location this will be found in the id_rsa.pub file and is used as the key that you will be uploading to your GitHub account.

### uploading key to GitHub
The first step of this process is to copy the generated key onto your clipboard,you will need to open up GitHub and then access the account section of the settings, from here you will need to find the SSH and GPG key section and then click onto new SSH key at this point you will paste the copied key into this section this will add the key onto your account and save it for future work.[add ssh key](https://github.com/settings/keys)
