# spacejam
# ioT notification system
# code
from plyer import notification
import time

def remind(title,message):
   notification.notify(
       title_=_title,
       message_=_message,
       app_icon_=_"https://vectorified.com/images/wellbeing-icon-13.png"
       timeout_=_20,
)

if __name__=='__main__':
    while True:
       remind("Hey Joey,take a break now !!","Take a power nap to keep your body and mind healthy")
       time.sleep(3600)
