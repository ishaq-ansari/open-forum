# Open Forum

Initially, designed to write and share poetries, Open Forum is a creative writing community platform for sharing thoughts, poems, stories, and ideas. It empowers users to express themselves, collaborate, receive feedback, and grow personally through writing and connection.

## Features

- Share your thoughts, poems, stories, and ideas
- Collaborate with other writers
- Receive feedback and engage in discussions
- Bookmark and like your favorite posts
- Participate in writing challenges and prompts
- Personal profiles with avatars and bios
- Secure authentication and user data policies
- Responsive, modern UI with dark mode support

## Getting Started

### Prerequisites

- Node.js (v18+ recommended)
- npm or yarn
- Supabase account (for backend)

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/ishaq-ansari/PoeticSouls.git
   cd PoeticSouls
   ```
2. Install dependencies:
   ```sh
   npm install
   # or
   yarn install
   ```
3. Set up Supabase:
   - Create a Supabase project
   - Copy the environment variables to `.env.local`
     Create a `.env.local` file at the project root and add the following values:

```env
VITE_SUPABASE_URL=https://your-supabase-url.supabase.co
VITE_SUPABASE_ANON_KEY=your-anon-key
```

      - Replace the placeholders above with your Supabase project URL and anon key (find them under Project Settings > API).

- Run migrations in `supabase/migrations/`

4. Start the development server:
   ```sh
   npm run dev
   # or
   yarn dev
   ```

## Project Structure

- `src/` — Frontend React code
- `supabase/` — Database migrations and backend setup
- `public/` — Static assets

## Technologies Used

- React + TypeScript
- Vite
- Supabase (PostgreSQL, Auth, Storage)
- Tailwind CSS

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License

MIT

## Contact

For questions or feedback, reach out via GitHub Issues or email ishaq.ansari@example.com.

---

Open Forum — Empower yourself and connect with others through creative writing.
