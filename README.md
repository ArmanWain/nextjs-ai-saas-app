# Next.js AI-Powered SaaS Application
AI-powered software as a service (SaaS) application built with Next.js. It allows users to:
- Create an account
- Transform images using AI
- View community image transformations
- Purchase credits to perform transformations

## Link to the Deployed Project
Below is a link to the deployed project:
<br/>
[Deployed Project](https://nextjs-ai-saas-app.vercel.app/)

You can use the following test card for payments:
<br/>
**4242 4242 4242 4242**

For the rest of the payment form, you can enter any information you like.

## Tech Stack
- Next.js
- TypeScript
- MongoDB
- Tailwind CSS
- Shadcn
- Cloudinary
- Stripe
- Clerk

## Features
- **Secure User Authentication**: Protect user data and enhance security with Clerk's authentication system.
- **Community Image Showcase**: Discover and get inspired by a gallery of user-generated image transformations.
- **AI-Powered Image Search**: Find images quickly by searching for specific content, leveraging cutting-edge AI recognition.
- **Advanced Image Restoration**: Repair and enhance old, damaged, or low-quality images to bring them back to life.
- **Custom Image Recoloring**: Easily modify images by swapping colors and applying unique color schemes to transform the mood or style.
- **Generative Fill Technology**: Seamlessly fill missing sections of images with AI-driven content, making them look complete and natural.
- **Smart Object Removal**: Effortlessly remove unwanted elements from your images while maintaining natural background consistency.
- **Background Removal & Isolation**: Isolate subjects from their background, perfect for creating clean, professional images for e-commerce or marketing.
- **Flexible Credit System**: Buy credits to unlock powerful AI-driven transformations, offering users flexibility in how they pay for the service.
- **Responsive UI/UX**: Experience a smooth and intuitive user interface across all devices, designed for optimal performance and ease of use.

## Project Setup
Follow these steps to set up the project locally on your machine.

### Environment Variables
Create a new file named `.env.local` in the root folder and add the following content:
```
#NEXT
NEXT_PUBLIC_SERVER_URL=http://localhost:3000

#MONGODB
MONGODB_URL=

#CLERK
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
CLERK_WEBHOOK_SECRET=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

#CLOUDINARY
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=
NEXT_PUBLIC_CLOUDINARY_UPLOAD_PRESET_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=

#STRIPE
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=
```
Fill in the missing values with your own. You can obtain these by signing up with each respective provider.

### Install Dependencies
```
npm i
```

### Run Server
```
npm run dev
```
You can now go to http://localhost:3000/ to view the app.