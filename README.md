# DiscordCalorieTracker

Friend was in need of a way to track calories using applications that were most convenient for him. As a user who sepnds a lot of time on discord, I made him a bot to track his calories for him to help him reach his calorie goal. <br />

Personalized calorie tracker.<br />
• Prompts user 3 times a day to enter meal description and calorie count.<br />
• Allows user to input extra calories through commands to include mid-day snacks.<br />
• Sends a final message at night to notify user whether or not calorie goal was met or not.<br />
• Stores user data in SQlite database. Accessibile through commands to view each specific days food and calories.<br />

## Commands
- `change_calorie_goal`
- `change_time`
- `count`
- `delete`
- `get_food_data`
- `help`
- `input_food`
- `list`
- `meal_times`
- `notify`
- `server`
- `user`

Plans to: <br />
• Expand to multiple servers using hash maps to store personal data including: guild, channel, and user ids.<br />
