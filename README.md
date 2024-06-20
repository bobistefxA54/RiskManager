# RiskManager

### This is a risk management bot for cTrader that allows you to input what % of your account you want to risk per trade and automatically adjusts your position size on pending orders, without having to look at online calculators.
---
### Step 1 
Open RiskManagementBot.cs and copy the code

### Step 2 
Open cTrader and navigate to the "Automate" tab
![image](https://github.com/bobistefxA54/RiskManager/assets/157811229/21b38887-2227-4177-9fd9-b3228fc73ed2)

### Step 3
Click on "New" to create a new bot and choose a name for it
![image](https://github.com/bobistefxA54/RiskManager/assets/157811229/252ee33c-3c7b-4ce7-82e9-d5b39696906b)

### Step 4
Click on the tab below the newly created bot's name and at the bottom of the screen you will be able to input the percentage of your account that you wish to risk on each position
![image](https://github.com/bobistefxA54/RiskManager/assets/157811229/8ac38259-3d23-4786-bcff-16cb4732fe23)

### Step 5
Click the green play button to run the bot

---
NOTE: The bot will calculate and adjust position sizing IF it's RUNNING and ONLY on pending orders. The position sizing will not be adjusted if the bot is not running.
