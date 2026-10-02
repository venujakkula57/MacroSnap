# 🥗 MacroSnap

MacroSnap is an AI-powered nutrition buddy built with Python, Streamlit, and Google's Gemini Vision API. Simply upload a photo of your meal or type a description, and the app instantly estimates your calories and macronutrients (Protein, Carbs, Fat). 

When you're done eating for the day, a single click summarizes your entire conversation and texts a neat summary directly to your phone via the Twilio WhatsApp API.

## Features
- **Multimodal Input:** Accepts both text descriptions and image uploads.
- **AI Vision Analysis:** Uses `gemini-3.5-flash` to identify food and estimate nutritional value without complex OpenCV/MediaPipe pipelines.
- **WhatsApp Integration:** Uses Twilio's Content API to send a formatted daily summary straight to the user's phone.
- **Stateful Chat:** Remembers conversation history across the session to provide accurate running totals.

## How to run locally

1. **Clone the repository:**
   ```bash
   git clone <your-github-repo-url>
   cd macrosnap