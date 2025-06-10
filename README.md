# Ada-EV - Electric Car Recommendation Website

A comprehensive electric car recommendation platform built with Next.js, featuring both public-facing pages and admin management system.

## Features

### Public Features
- **Homepage**: Welcome page with hero section and feature highlights
- **Car Listing**: Display all electric cars with detailed specifications
- **Recommendation System**: Form-based car recommendation with personalized results
- **Responsive Design**: Works seamlessly on desktop and mobile devices

### Admin Features
- **Admin Authentication**: Secure login system for administrators
- **Admin Dashboard**: Overview with statistics and car management
- **CRUD Operations**: Complete Create, Read, Update, Delete functionality for cars
- **Car Management**: Add, edit, and delete electric cars with specifications

### Car Data Structure
Each electric car includes:
- **Merek** (Brand)
- **Model**
- **Harga** (Price in Indonesian Rupiah)
- **Baterai** (Battery capacity in kWh)
- **Tenaga** (Power in HP)
- **Jarak** (Range in km)
- **Kecepatan Maks** (Max speed in km/h)
- **Image** support

## Tech Stack

- **Framework**: Next.js 14 with App Router
- **Styling**: Tailwind CSS + shadcn/ui components
- **Language**: TypeScript
- **Icons**: Lucide React
- **Database Ready**: Prepared for Supabase integration

## Getting Started

1. Clone the repository
2. Install dependencies:
   \`\`\`bash
   npm install
   \`\`\`
3. Run the development server:
   \`\`\`bash
   npm run dev
   \`\`\`
4. Open [http://localhost:3000](http://localhost:3000) in your browser

## Admin Access

- **Username**: admin
- **Password**: admin123

## Project Structure

\`\`\`
├── app/
│   ├── page.tsx                 # Homepage
│   ├── cars/page.tsx           # Car listing page
│   ├── recommendation/page.tsx  # Recommendation system
│   └── admin/
│       ├── login/page.tsx      # Admin login
│       ├── dashboard/page.tsx  # Admin dashboard
│       └── cars/add/page.tsx   # Add new car
├── components/
│   ├── layout/navbar.tsx       # Navigation component
│   └── ui/                     # shadcn/ui components
├── lib/
│   └── types.ts               # TypeScript interfaces
└── public/                    # Static assets
\`\`\`

## Features to Add

- [ ] Database integration with Supabase
- [ ] Real image upload functionality
- [ ] Enhanced recommendation algorithm
- [ ] User reviews and ratings
- [ ] Car comparison feature
- [ ] Search and filtering
- [ ] Email notifications

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License.

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

\`\`\`bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
\`\`\`

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
