# upwork-bot

This bot pushes the new job from upwork to telegram based on the
search keywords.

It also uses redis to store hashes of the urls so that repeated 
jobs doesn't flood the telegram bot.

Right Now it provide jobs in simple format!
1. Link
2. Title
3. Day (how old the gig is) btw I have put condition of not more than 2 days
4. Budget / Hourly Rate
5. Category


Features to be added.
1. Add multi-chat support, right now it contains static chat-id
2. Able to manipulate the search terms using telegram (only admin)
3. Feature to flush the redis keys from telegram (only admin)
4. Feature to manipulate filters for search
5. Add country in the message
6. Store the jobs data into persistent database.
7. Using persisited data, extract several insights like 'dominant techonology', 'country vs hiring rates', etc.
8. Create Dashboard to show those insights

