# Bulk message automation in Whatsapp
- - - - - 
## Aim
Aim of this script is to automate the process of sending messages on whatsapp. Although we cannot call it a complete automation as it is mandatory for the user to scan the QR code
himself from his phone, this script allows us to choose the name of the person or group we wish to send a message to along with the number of messages to be sent. We can also tweak the sleep time i.e. the interval at which the messages will be sent.
Selenium is a very smart package in python with which developer’s can automate the browser’s activity. With this we can make use of whatsapp-web through the browser.

## Requirements

```pip install selenium```</br>
```pip install webdriver_manager```

## Steps to use
```
- Run ```python message-automation.py```
- Scan the QR code to open whatsapp web.
- Inside the terminal, enter the exact name of the group/person as is stored in your whatsapp contacts
- Enter the number of times you wish the message to be sent
- Wait for a few seconds and see the automation :)
```
## Example output
Here as seen, the target recepient has received the message 10 times automatically without us needing to type it in the whatsapp text bar.

![alt-text](https://github.com/TaniaMalhotra/hacking-tools-scripts/blob/whatsapp-automation/Python/whatsapp-automation/ezgif.gif)
