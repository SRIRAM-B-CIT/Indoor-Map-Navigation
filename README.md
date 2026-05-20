# NavX - Indoor Navigation System

## Demo Links

- Live app: [https://cit-maps.vercel.app/navigate](https://cit-maps.vercel.app/navigate)
- Demo video: [Google Drive](https://drive.google.com/file/d/1GQh00n_zqIyaizncatNpfZbP1uYgX6Qq/view?usp=drivesdk)
NavX is an indoor navigation system for college campuses with multi-map routing, QR-based start selection, an AI chatbot, and an admin map editor.

## Quick Start

```bash
git clone https://github.com/SRIRAM-B-CIT/Indoor-Map-Navigation.git
cd Indoor-Map-Navigation
npm install
npm run dev
```

Open `http://localhost:3000` in your browser.

## Key Features

- Multi-map navigation across campus, building, and floor levels
- Gateway nodes for cross-map routing
- AI chatbot for natural-language destination search
- Admin dashboard for map upload, editing, and node management
- QR code support for quick starting locations
- Responsive UI built with Next.js, TypeScript, Tailwind CSS, and Canvas

## Scripts

- `npm run dev` - Start the dev server
- `npm run build` - Build the app
- `npm start` - Start the production server
- `npm run lint` - Run ESLint

## Environment

Create a `.env` file with the values your deployment needs:

- `MONGODB_URI`
- `NEXTAUTH_URL`
- `NEXTAUTH_SECRET`
- `NEXT_PUBLIC_USE_DATABASE`
- `ADMIN1_USER`
- `ADMIN1_PASS`
- `ADMIN2_USER`
- `ADMIN2_PASS`
- `MAP_UPDATE_PIN`

## Project Structure

- `src/app` - Pages and API routes
- `src/components` - UI components
- `src/lib` - Database, auth, image, and pathfinding helpers
- `src/models` - MongoDB models
- `src/types` - Shared TypeScript types
- `public/maps` - Map assets

## Support

- Issues: [GitHub Issues](https://github.com/SRIRAM-B-CIT/Indoor-Map-Navigation/issues)
- Discussions: [GitHub Discussions](https://github.com/SRIRAM-B-CIT/Indoor-Map-Navigation/discussions)
