## [Next.js](https://nextjs.org/learn/react-foundations/what-is-react-and-nextjs) + [TailwindCSS](https://tailwindcss.com/docs/installation/using-postcss)

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).


****
## Installation & Packages Used :
````bash
npm i byrypt
npm i mongodb
npm i mongoose
npm i next-auth
npm i byrypt
npm run dev
````
****
## ENV :
```env
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET_KEY=
MONGODB_URI=[mongodb+srv]

NEXTAUTH_URL=
NEXTAUTH_URL_INTERNAL=
NEXTAUTH_SECRET=[npx auth secret] OR [openssl rand -base64 32]
```
**References for ENVs:**
- [Google Console - Free](https://console.cloud.google.com/)
- [MongoDB - Free](https://cloud.mongodb.com)
- [NEXTAUTH](https://next-auth.js.org/configuration/options#environment-variables)

Open [[http://localhost:3000](http://localhost:3000)] with your browser to see the result.
****
## Tested Hooks :
````
import Link from "next/link";
import Image from "next/image";
import { useEffect, useState } from "react";
import NextAuth from "next-auth";
import { signIn, signOut, useSession, getProviders, SessionProvider } from "next-auth/react";
import GoogleProvider from "next-auth/providers/google";
import mongoose, { Schema, model, models } from "mongoose";
import { usePathname, useRouter, useSearchParams } from "next/navigation";
````
****