# Twitter-Update-Handle-P
This script will monitor a twitter handle and attempt to take it when it becomes available.

## Installation Instructions
1. Obtain the following by applying to be a twitter developer. A quick "how-to" google search could get you there [or even a youtube video](https://www.youtube.com/watch?v=G_CX4HzOi94&ab_channel=StevesieData).
    - Consumer Key
    - Consumer Secret
    - Access Token
    - Access Token Secret
    
    **Note**: Don't share these values with others

2. Copy/paste the items from step 1 and paste them into the config.json file 
3. Enter your desired twitter handle name into the config.json
4. Enter the number of threads into the config.json (suggested is 1. Anything above will eventually become rate limited).
3. In a terminal, navigate to the files obtained from this github repo and install the additional libraries: `pip install -r requirements.txt`
4. Run the .exe, sit back & enjoy!
