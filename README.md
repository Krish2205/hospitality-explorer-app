# Hospitality Explorer App

A React 18 application for searching and comparing hotels using the Amadeus API and Supabase Authentication.

## Features
- **Authentication**: Secure Login/Signup via Supabase.
- **Hotel Search**: Real-time data fetching from Amadeus API.
- **Pagination**: "Load More" functionality for search results.
- **Comparison**: Select up to 4 hotels to view price/rating charts via Recharts.
- **Persistence**: Comparison list saved in Local Storage.

## Setup Instructions
1. Clone the repo: `git clone <your-repo-url>`
2. Install dependencies: `npm install`
3. Create a `.env` file in the root and add:
   - VITE_SUPABASE_URL=https://ymzcboflpadumovxgbwq.supabase.co
   - VITE_SUPABASE_ANON_KEY=sb_publishable_NDNVjX-Aqa1_BfETGeE-8w_Sut8KJYs
   - VITE_AMADEUS_CLIENT_ID=3uwAKSkwHrqSSLtLydt4FhSbDrCovGve
   - VITE_AMADEUS_CLIENT_SECRET=EUhQ6h0LzM3YGoOG
4. Start the app: `npm run dev`

## Deployment
Live URL: [Link to your Vercel deployment]
