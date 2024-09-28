# LanzeDataBot
This is a bot to help out the growing Quest Master community!
It is linked to the [Quest Master Dashboard](https://lookerstudio.google.com/u/0/reporting/598e2a3a-6d06-4d08-ac53-2a53a91dd1c2/page/NlGBE) and uses the same data.
Please note that there is a delay of up to an hour for the data.
The data for this bot and the dashboard is updated at the top of the hour and depending how many changes there were compared to the previous update may take anywhere from 3 to 7 minutes.

# Make sure to mod the bot

# Queues
This bot can handle a queue to support with viewer requested levels.
You have multiple commands to control the size of the queue, select random levels, skip levels, see the estimated time of the entire queue, etc.

| Image | Command | Description | Min Parameters | Max Parameters |
|:---------|:---------:|:---------:|:---------:|:---------:|
| ![image](https://github.com/user-attachments/assets/cf5d2a78-a086-4a62-a0e9-7409c406e048) | !qmadd | Adds a level to the queue. (limit of 2 per user, 10 for the streamer). This checks to make sure a level is actually valid or not. Default size of queue is 20. You can set using !qmlimit | 1 | 1 |
| ![image](https://github.com/user-attachments/assets/7bef43bd-d532-4357-b095-98e0a24d66c8) | !qmskip | Pushes the current level to the end of the queue (streamer only) | 0 | 0 |
| ![image](https://github.com/user-attachments/assets/a0bfd4bb-a5f2-4ace-b9aa-b25c6aca2064) | !qmrandom | Get a random level from the queue and swap it with the current one | 0 | 0 |
| ![image](https://github.com/user-attachments/assets/11c8aac1-0528-4711-959d-c4655eaa0062) | !qmcurrent | Shows the current level in the queue | 0 | 0 |
| ![image](https://github.com/user-attachments/assets/656ab3b1-25c3-46eb-9bee-3f742eb5d0e0) | !qmnext | Shows the next level in the queue | 0 | 0 |
| ![image](https://github.com/user-attachments/assets/f5483576-795e-42f6-b9a9-9c54d13f864c) | !qmgg | Removes the current level from the queue | 0 | 0 |
| ![image](https://github.com/user-attachments/assets/7bef43bd-d532-4357-b095-98e0a24d66c8) | !qmqueuewipe | Resets your queue | 0 | 0 |
| ![image](https://github.com/user-attachments/assets/2c94b288-b128-41bc-8ec6-9aaa5eed9f95) | !qmqueuesize | Shows how many levels are in the queue | 0 | 0 |
| ![image](https://github.com/user-attachments/assets/82e99e78-8f58-4bc7-871b-6f002a6de1a6) | !qmqueuetime | Shows estimated time based on average clear times | 0 | 0 |
| ![image](https://github.com/user-attachments/assets/d39eda84-7d8c-4f61-8a5a-87b97883eb45) | !qmlimit | Limits how many levels can be in your queue (1 - 30) | 1 | 1 |

# Team 0%
Simple commands are available to support players on their mission of leaving no level behind.
Try !qmzero to get a random uncleared level or !qmzerocheck to see how many levels remain.

| Image | Command | Description | Min Parameters | Max Parameters |
|:---------|:---------:|:---------:|:---------:|:---------:|
| ![image](https://github.com/user-attachments/assets/a0bfd4bb-a5f2-4ace-b9aa-b25c6aca2064)| !qmzero | Gets a random uncleared level | 0 | 0 |
| ![image](https://github.com/user-attachments/assets/03cbc488-f264-49b2-8e7c-506ebcd0ed7b) | !qmzerocheck | Shows the Team 0% progress | 0 | 0 |

# Endless Challenge
The game doesn't have this feature but will one day, until then you can do an endless challenge via the bot!
!qmvalidate to first sync up your ingame name to your twitch account.
!qmstart <difficulty> to start a challenge

Available difficulties: easy, normal, expert, super expert
Difficulty categories are determined by their overall clear rate.

We do have leaderboard rankings for each of the difficulties! GLHF

| Image | Command | Description | Min Parameters | Max Parameters |
|:---------|:---------:|:---------:|:---------:|:---------:|
| ![image](https://github.com/user-attachments/assets/adf65775-2b67-4f44-8b0c-8c39071f09f3) | !qmvalidate | Validates the user profile with the provided game username | 1 | 1 |
| ![image](https://github.com/user-attachments/assets/885ae3dc-0eab-44d5-9658-04f2f8601fd7) | !qmstart | Starts a new endless challenge run based on difficulty | 1 | 1 |
| ![image](https://github.com/user-attachments/assets/895dbe67-3f62-44ce-a27d-c62ee7cd9490) | !qmbeat | Marks the current level as beaten during a challenge run | 0 | 0 |
| ![image](https://github.com/user-attachments/assets/d7ca5eef-68ec-4acb-b729-c58b19de665c) | !qmdead | Marks a death in a level and decreases a life count during a challenge run | 0 | 0 |
| ![image](https://github.com/user-attachments/assets/2a078a0e-d699-4574-9c79-948a7e3b3b6d) | !qmpass | Skips the current level using a skip, if any are available | 0 | 0 |
| ![image](https://github.com/user-attachments/assets/0de42c48-05cd-43fe-a81c-68273991c17f) | !qmstatus | Shows current challenge status including lives and skips left | 0 | 0 |
| ![image](https://github.com/user-attachments/assets/d8765d99-373b-4747-97eb-bebbf46970f0) | !qmrank | Shows leaderboard for a specific difficulty | Challenge Run | 1 | 1 |
| ![image](https://github.com/user-attachments/assets/7fbee5e8-7731-4527-a5ec-ecd3ce3795be) | !qmrestart | Forcefully ends the current challenge run and validates completed levels | 0 | 0 |

# Other Commands
The bot has the following commands available:

| Image | Command | Description | Type | Min Parameters | Max Parameters |
|:---------|:---------:|:---------:|:---------:|:---------:|:---------:|
| ![image](https://github.com/user-attachments/assets/c6ffafd1-45e4-41f5-a179-75b3b5e38dea) | !qmcommands | Get a link to this page | Info | 0 | 0 |
| ![image](https://github.com/user-attachments/assets/e15a23ff-9104-42f8-b1e1-42d393c93cc8)| !qmlevel | Look up details about the input level id | Info | 1 | 1 |
| ![image](https://github.com/user-attachments/assets/55a602a2-63b9-42d6-b8af-17bd6927bd3c) | !qmwrcheck | Shows the # of WR for the input user | World Record | 1 | 1 |
| ![image](https://github.com/user-attachments/assets/4873c6af-10f2-4cda-8d51-9b25cd0bb52a) | !qmcredits | Shows who created the bot and who helped | Info | 0 | 0 |
| ![image](https://github.com/user-attachments/assets/1ffe73a2-6e96-4e34-9e27-50e824ce239d) | !qmdashboard | Shows a link to the dashboard | Info | 0 | 0 |
| ![image](https://github.com/user-attachments/assets/3dc2ebe6-8723-4898-add5-e78e9c2cd1e2) | !qmfalladd | Provides a link to the qmFall emote on BTTV | Fun | 0 | 0 |
| ![image](https://github.com/user-attachments/assets/a0ba4861-b580-4f67-bf68-d406d9f05379) | !qmfall | Responds with "qmFall qmFall qmFall" | Fun | 0 | 0 |
