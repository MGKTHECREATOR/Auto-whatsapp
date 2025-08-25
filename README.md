📱 Auto WhatsApp Messenger

Automate your **WhatsApp messages** with ease!
This project uses **Python** and **pywhatkit** to send WhatsApp messages automatically, saving time and effort.

🚀 Features

* ✅ Send WhatsApp messages at a scheduled time
* ✅ Simple and lightweight (just a few lines of code)
* ✅ Works directly with WhatsApp Web
* ✅ Supports text, images, and even group messages
* ✅ Perfect for reminders, alerts, and fun messages 🎉

🛠️ Requirements

* Python 3.x
* Libraries:

  bash
  pip install pywhatkit pyautogui pillow
  

▶️ How to Run

1. Clone this repository:

   bash
   git clone https://github.com/yourusername/auto-whatsapp.git
   cd auto-whatsapp
   
2. Run the script:

   bash
   python auto_whatsapp.py
   
3. WhatsApp Web will open automatically, and your message will be delivered at the scheduled time.

💡 Example Usage

python
import pywhatkit as kit  

Send message at 10:30 AM  
kit.sendwhatmsg("+911234567890", "Hello, this is an automated test!", 10, 30)  

🔮 Future Upgrades

* Add **GUI interface** for non-coders
* Support for **multiple scheduled messages**
* Integrate with **Google Calendar / To-Do apps**
* Add **voice message automation** 🎙️

⚡ Why This Project?

In today’s fast-paced world, reminders and automation are lifesavers.
This project shows the **power of Python** in automating daily tasks and making communication effortless.

📜 License

This project is licensed under the MIT License.
