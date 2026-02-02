# Stock News Whatsap Alert (TSLA)
- Pulls daily stock prices from Alpha Vantage
- Calculates the percentage change from yesterday vs. the day before
- If the move is bigger than a threshold, it fetches the top 3 related news articles from NewsAPI

## Requirements
- Twilio WhatsApp Sandbox enabled (or approved WhatsApp sender)
- Intalled dependencies: ```pip install requests twilio```

## API Keys/Enviroment variables
- ALPHAV_API_KEY (Alpha Vantage)
- NEWS_API_KEY (NewsAPI)
- TWILIO_SID (Twilio Account SID)
- TWILIO_AUTH_TOKEN (Twilio Auth Token)

## Notes
- To receive messages, your phone number must be joined to the sandbox first.
