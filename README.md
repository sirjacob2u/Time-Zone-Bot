# Time-Zone-Bot
Time zone bot for discord. \n
Also has a feature to send a happy birthday message in a specefied channel ID

---

## Initial setup

Use pip to install the requiremnts using
```bash
pip install -r requirements.txt
```

Then run the code using 
```bahs
python3 clock.py
```

Below is an example of the bot starting

![Example](https://github.com/sirjacob2u/Time-Zone-Bot/blob/main/Starting.png?raw=true "Sucess")

---

## Daylight savings time

The bot has the ability to toggle daylight savings time. Since some regions don't observe daylight savings time this seemed like the easiest way to implemnt this. To enable and disable daylight savings time just type 

```
$daylight yes 
```

and to disable daylight savings time type 

```
$daylight no
```

---
## Birthday message 

The bot can also send a message for a specified users birthday to a specified user. The data for the birthdays are stored in the code where  `dt.date(year,month,day)` 

```python
# List of birthdays
BIRTHDAY_LIST = {
'null': dt.date(2003, 1, 1),
'null': dt.date(2003, 1, 1),
'null': dt.date(2002, 1, 1),
'null': dt.date(2000, 1, 1),
'null': dt.date(2000, 1, 1),
```

To set the channel the bot sends the mesage in. Set the number located at line 18 to the channel ID of the discord channel. 

```python
message_channel_id=555555555555555555
```

---

Thats is. This bot really is simple. Feel free 
