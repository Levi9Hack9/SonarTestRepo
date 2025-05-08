# Hack9 Scoring

AI-powered scoring system for coding competitions using Azure OpenAI.

## Features

- Submit GitHub repository URLs for automated scoring
- Include deployed website URLs for enhanced UX/UI quality assessment
- AI evaluation based on multiple criteria:
  - Feature Coverage
  - Code Quality
  - Documentation
  - Test Coverage
  - Project Board Usage
  - Functionality
  - UX/UI Quality
  - 3rd Party Integrations
- Detailed scoring with explanations for each category

## Tech Stack

- Next.js 14 with App Router
- TypeScript
- Tailwind CSS
- Azure OpenAI for AI evaluation
- React Hook Form with Zod validation

## Getting Started

### Prerequisites

- Node.js 18.17 or later
- npm or yarn
- Azure OpenAI API access

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/hack9-scoring.git
cd hack9-scoring
```

2. Install dependencies:

```bash
npm install
# or
yarn install
```

3. Set up environment variables:
   
   Copy the `.env.local` file and update it with your Azure OpenAI credentials:

```
AZURE_OPENAI_ENDPOINT=your-azure-openai-endpoint
AZURE_OPENAI_API_KEY=your-azure-openai-api-key
AZURE_OPENAI_DEPLOYMENT_NAME=your-deployment-name
```

4. Run the development server:

```bash
npm run dev
# or
yarn dev
```

5. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Deploy on Vercel

The easiest way to deploy this app is to use the [Vercel Platform](https://vercel.com/new) from the creators of Next.js.

## How it Works

1. Users submit a GitHub repository URL
2. The application uses Azure OpenAI to analyze the repository
3. The AI evaluates the code based on multiple criteria
4. Results are displayed with scores and explanations for each category

## Further Development

- Add user authentication
- Store evaluation history
- Add comparison feature between repositories
- Generate detailed reports with improvement suggestions
