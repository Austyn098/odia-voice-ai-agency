
# ODIA Voice AI Agency

A fully autonomous, legally compliant Voice AI Agency built for Nigeria.

## 🚀 Features
- Outbound voice calls (sales, lead gen, reminders)
- Auto appointment scheduling via voice
- WhatsApp voice reply agent
- Flutterwave billing & CRM integration
- Built with: Next.js, Supabase, Whisper, ElevenLabs, GPT-4o

## 🛠 Tech Stack
- Frontend: Next.js, TailwindCSS
- Backend: Supabase (Postgres + Auth)
- Voice: Whisper (STT) + ElevenLabs (TTS)
- Logic: GPT-4o via OpenAI API
- Payment: Flutterwave
- Infra: Vercel for deployment

## 📦 How to Deploy
1. Clone this repo
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create `.env.local` with:
   ```
   OPENAI_API_KEY=
   ELEVENLABS_API_KEY=
   SUPABASE_URL=
   SUPABASE_KEY=
   FLUTTERWAVE_SECRET_KEY=
   ```
4. Run locally:
   ```bash
   npm run dev
   ```
5. Deploy on Vercel and connect your Supabase project

## 🧠 Legal Compliance
- NDPR audio disclosure
- Opt-in policy on voice capture
- Auto invoice via Flutterwave webhook

## 📞 Example Call Flow
1. User visits landing page
2. Signs up → Enters business info
3. Agent is instantly deployed
4. Calls begin in <5 minutes
