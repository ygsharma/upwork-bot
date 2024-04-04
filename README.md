# Upwork Job Alert Bot

This Upwork Job Alert Bot is a fully automated system designed to streamline the job search process on Upwork. It automatically pushes new job postings from Upwork to a designated Telegram chat based on specific search keywords, helping users stay ahead in the competitive freelance market.

## Features

- **Immediate Job Alerts:** Sends real-time job postings directly to Telegram.
- **Duplicate Control:** Utilizes Redis to store URL hashes and prevent duplicate job notifications.
- **Simplified Job Information:** Presents jobs with essential details including link, title, post age, budget/rate, and category.

## Current Job Information Format

1. **Link:** Direct URL to the job posting.
2. **Title:** Name of the job.
3. **Day:** Age of the posting (up to 2 days old).
4. **Budget / Hourly Rate:** The proposed budget or hourly rate for the job.
5. **Category:** The field or sector the job is categorized under.


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/username/upwork-bot.git
   ```

2. Navigate to the project directory:
   ```bash
   cd upwork-bot
   ```

3. Install the required dependencies:
   ```bash
    pip install -r requirements.txt
   ```
4. To run the bot, execute the following command in the project directory:
   ```bash
   python upwork_bot.py
   ```


## Planned Features

- Multi-chat support for notifications across various Telegram chats.
- Admin-only command to modify search terms directly via Telegram.
- Admin-only command to clear Redis keys via Telegram.
- Enhanced filter options for more refined job search results.
- Inclusion of country information in job messages.
- Database integration for persistent storage of job data.
- Data analysis tools to extract insights such as trending technologies and hiring rates by country.
- A comprehensive dashboard to display these insights.
