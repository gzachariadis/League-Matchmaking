# League-Matchmaking

An advanced Auto Queue Script for League of Legends and more...


- Login Summoner


- Get Game State 
	- If GameState is Already Chosen Lobby, then start Matchmaking Q ---> place in Q
	- if GameState is No Map Selected, then Ask for Which Q to Join -----> lobby creator

- Check if user is in Q and start Timer
	- if Q aborted, go back lobby.
	- Else Accept Q when it pops.
		- Check if Match Already Accepted

Champ Select

- Declaring Phase

   - Wait until Declare time is over.
	 - Retrieve Hovered - Declared Champions (for Team)

- Ban Phase

  - Choose a bannable champion --> Jungler 55% of the time, ban top laner 10% of time, ban midlane 20% of time, ban supp 5% of time, ban adc 10% of time
	- Check against Hovered Champions, if id not found in Hovered ---> Ban else --> Choose a bannable champion again until a ban is completed

- Pick Phase
  -  Choose Champion to pick
	-  Check if Available
	-  Pick it
	-  Lock Champion
	-  Choose Rune Page that Matches Champion Name
	-  Choose Exhaust - Ignite as Summoner Spells
	-  Print Match Begins when Game State Changes.

## Sources

- [The ultimate anti-flaming tool](https://www.reddit.com/r/leagueoflegends/comments/tmzygo/the_ultimate_antiflaming_tool/)
- [MostlyPride - LolCloser](https://github.com/MostlyPride/LolCloser)
- [Git-Lukyen - LoL-AutoReport](https://github.com/Git-Lukyen/LoL-AutoReport)
- [League of Legends Auto Accept and Statistic Checker](https://www.youtube.com/watch?v=6b4XHmcfNio)
- [League-of-Legends-Auto-Accept-and-Match-Checker](https://github.com/AulaMaroon/League-of-Legends-Auto-Accept-and-Match-Checker/blob/main/autoaccept.py)
- [I made a script which auto-accept games, prepick your champ, ban the champ you want, pick your champ and alert you when your game started (Made for Ranked / Draft)](https://www.reddit.com/r/leagueoflegends/comments/x3y8qw/i_made_a_script_which_autoaccept_games_prepick/)
- [auxermen - auto_accept_ban_pick.py](https://gist.github.com/auxermen/d44019816cdc96d62eca860dffe459f4)
- [LCU-Schema Tool](https://www.mingweisamuel.com/lcu-schema/tool/#/)
- [How to win your Solo Queue Draft - a statistical analysis of 1M+ games](https://www.reddit.com/r/summonerschool/comments/xcd5nl/how_to_win_your_solo_queue_draft_a_statistical/)
- [TurboSmurfs](https://turbosmurfs.gg/product/40000-blue-essence-smurf-eune)
- [How to Set Runes using LCU](https://hextechdocs.dev/how-to-set-runes-using-lcu/)
- [GitLukyen - AutoReport](https://github.com/Git-Lukyen/LoL-AutoReport)
