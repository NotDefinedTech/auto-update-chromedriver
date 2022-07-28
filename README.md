# When Chrome's constant updates break your chromedriver scripts
You can run this shell script to automatically get the appropriate chromedriver version for the version of Chrome on your Mac. It finds that correct chromedriver, downloads it, unzips and overwrites the old chromedriver file.

Watch a full walkthrough of this script: https://www.youtube.com/watch?v=d3XOkEvLR64


## Requirements
- Mac: This script was written for Mac, but it should be editable to suit other operating systems. Start by changing your paths to find Google Chrome version. Then change which zip file on the chromedriver download page to target. A written walkthrough is available here, which might help guide you through all of the compound steps: https://notdefined.tech/blog/how-to-automatically-update-chromedriver-for-selenium-when-chrome-updates/

- unzip utility: If the unzip command isn't already installed on your system, then run:
sudo apt-get install unzip
https://askubuntu.com/questions/86849/how-to-unzip-a-zip-file-from-the-terminal


## How to use
1. Put this shell script in the same directory as your current chromedriver file.
2. Open your terminal and cd to that directory
3. Change permissions on this script to be executable: ```chmod +x get-latest-chromedriver.sh```
4. Run the script! ```./get-latest-chromedriver.sh```
