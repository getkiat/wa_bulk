# wa-blk

Whatsapp Bulk Messenger uses selenium to automate sending of messages via Whatsapp Web.

# Requirements
*  Python 3.x
*  Chrome v79 <a href =
"https://chromedriver.storage.googleapis.com/2.42/chromedriver_mac64.zip">ChromeDrive MAC Download</a>

# Setup

1. Install python - v3.x
2. Run `pip install -r requirements.txt`

# Steps

1. Enter the message you want to send inside `message.txt` file.
2. Enter the list of numbers line-separated in `numbers.txt` file.
3. Run `python automator.py`.
4. Once the program starts, you'll see the message in message.txt and count of numbers in the numbers.txt file.
5. After a while, Chrome should pop-up and open web.whatsapp.com.
6. Scan the QR code to login into whatsapp.
7. Press `Enter` to start sending out messages.
8. Sit back and relax!

# Credits
This tool was built by Anirudh Bagri 
*  www.github.com/anirudhbagri
