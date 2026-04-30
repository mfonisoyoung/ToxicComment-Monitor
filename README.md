## Toxic Comment Monitor Tool

An automation tool that monitors YouTube comments, analyzes sentiment, and detects potentially negative or toxic comments. It helps creators quickly identify comments that may need review, moderation, or removal.

## What this AI tool actually does (important clarity):
It does NOT:
❌ automatically delete comments
❌ decide what is “bad” with certainty

It DOES:
✅ flag potentially negative comments
✅ categorize sentiment (positive/neutral/negative)
✅ highlight toxic or abusive language
✅ send you a review list

 
## Full System Breakdown
1. Input Layer
Connect to: YouTube API (or comment scraping via automation tool like Make.com)
Fetch:
-New comments
-Video ID
-Author
-Timestamp

3. Preprocessing
   Clean data:
   -Remove emojis if needed
   -Normalize text (lowercase, trim spaces)
   -Filter spam patterns

5. AI Sentiment Analysis Layer
Each comment is analyzed for:
-Positive 😊
-Neutral 😐
-Negative 😡
-Toxic/abusive 🚨

7. It can also detect:
   -insults
   -hate speech
   -spam
   -harassment

9. Scoring System
    Each comment gets a score:
   Example:
   -Positive → 0–30
   -Neutral → 30–60
   -Negative → 60–80
   -Toxic → 80–100 (high priority flag)

11. Output Layer
it Send results to:
-Google Sheets dashboard OR
-sends you a direct Email summary OR
- sends a message to your Telegram/Discord alert

## Example output:
Comment text
-Score
-Category
-Suggested action (ignore/review/flag)
