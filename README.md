# RAJ GFX Pro Portfolio
A public professional portfolio plus a separate private admin dashboard.

## Setup
1. Create a Supabase project.
2. In Authentication > Users, create your admin user.
3. Create a PUBLIC Storage bucket named `portfolio`.
4. Run `supabase.sql` in SQL Editor.
5. Copy `.env.example` to `.env.local` and fill in your Supabase URL + anon/publishable key + social links.
6. `npm install` then `npm run dev`.
7. Deploy to Vercel/Netlify and add the same environment variables.

Replace YOUR-DOMAIN.com in public/robots.txt and public/sitemap.xml after choosing your domain.

Never use a Supabase service-role key in frontend code.
