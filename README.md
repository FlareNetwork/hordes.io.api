# How the API Calls are Working ?
The Base of all API Calls is: https://www.flareco.net/api/hordes.io.api.php

Now you can send a GET or a POST Request to this BASE URL.
With the following parameters:

?username=YOUR_USERNAME

now you can query the data.
(Currently Avaible Data: name, level, class, fame, clan, faction, exp, needexp)

Get all Character Data via "all" parameter.

EX: https://www.flareco.net/api/hordes.io.api.php?username=flareco&all

{"name": FlareCO, "level": 18, "class": archer, "fame": 101, "clan": NO CLAN, "faction": Bloodlust, "exp": 1843, "needexp": 7035}

All Other Methods: (*format is plain text)

EX: https://www.flareco.net/api/hordes.io.api.php?username=flareco&name //Returns the Custom Name of the User.

EX: https://www.flareco.net/api/hordes.io.api.php?username=flareco&level //Returns the Level of the User

EX: https://www.flareco.net/api/hordes.io.api.php?username=flareco&class //Returns the Class of the User

EX: https://www.flareco.net/api/hordes.io.api.php?username=flareco&fame //Returns the Fame of the User

EX: https://www.flareco.net/api/hordes.io.api.php?username=flareco&clan //Returns the Clan of the User.

EX: https://www.flareco.net/api/hordes.io.api.php?username=flareco&faction //Returns the choosen Faction

EX: https://www.flareco.net/api/hordes.io.api.php?username=flareco&exp //Returns the Current EXP

EX: https://www.flareco.net/api/hordes.io.api.php?username=flareco&needexp //Returns the NeededEXP for next Level

EX: https://www.flareco.net/api/hordes.io.api.php?username=flareco&skill={1-4} //Returns the Skill name
