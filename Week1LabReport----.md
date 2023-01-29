# Installing VScode
1. Go to the Visual Studio Code website (<https://code.visualstudio.com>) 
2. Download the installer on your computer
3. Click the installer and follow the instruction to dowload Visual Studio Code to your computer
4. You should get the screen like this after you finish
![Image](https://github.com/whc004/cse15l-lab-reports/blob/70daaef25472c4934067b715b0f77733a5cea466/Screen%20Shot%202023-01-12%20at%2012.43.54%20PM.png)
# Remotely Connecting
1. Look up your username here(<https://sdacs.ucsd.edu/~icc/index.php>)
2. Input your UCSD username and PID to find your username (your username should begin with cs15lwi23)
3. Reset your password after you get your username
4. Wait for 15 minute (the new password would take up to 15 minutes for your password to go into effect)
5. If you are using Windows not Mac, you need to download git (Use git bash in Visual Studio Code)
6. Open your VScode
7. Open a new terminal on your VScode
8. Enter the following line on the terminal (YOUR_ACCOUNT_NAME is the account name you just find out) 
   ssh YOUR_ACCOUNT_NAME@ieng6.ucsd.edu
9. Enter your password and press enter (Don't worry about the password do not show up, just type your password and press enter)
10. You should get the screen like this after you log in successfully
![Image](https://github.com/whc004/cse15l-lab-reports/blob/37758d5e45221576f1c841e2f3f53d685a7ea7e1/Screen%20Shot%202023-01-12%20at%201.40.47%20PM.png)

# Trying Some Commands
1. After you log in successfully, try some command such as, ```cd ~``` ,```cd```, ```ls -lat``` and ```ls -a```.
For instance: ![Image](https://github.com/whc004/cse15l-lab-reports/blob/b8b34b46fedf79ccee5e4b3d90a53f179ec3869e/Screen%20Shot%202023-01-12%20at%201.44.51%20PM.png)
2. Log out of the remote server in your terminal by using the command : ```exit```
