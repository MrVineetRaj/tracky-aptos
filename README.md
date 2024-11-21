# Tracky [Demo](https://tracky-flame.vercel.app/)

_Take command of your life_

A Web App Created using `Next JS` for tracking

- User Habits
- Nutritional Intake

Some other Features are

- User can generate a recipie using AI
- And ther is a leaderboard that shows where you stand among all usrs

## Setup

### For Running interface

- `npm run dev`
- setup `.env.local`

  ```bash
    AUTH_SECRET=
    GITHUB_CLIENT_ID=
    GITHUB_CLIENT_SECRET=

    MONGODB_URI=
    NEXT_PUBLIC_CONTRACT_ADDRESS=
    NEXT_PUBLIC_MODULE_NAME=

    CALORIE_NINJA_API_KEY=

    NEXT_PUBLIC_GEMINI_API_KEY=
  ```

- `npm run dev`

### For running Move files (using aptos CLI)

- `aptos move clean`
- `aptos move compile`
- `aptos move publish`

While deploying keep in mind about the addresses that has to be used
