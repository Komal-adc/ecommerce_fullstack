
<h1 style="color:yellow; font-weight:bold;;" >Required Installation</h1>

VSCODE

Node.js

Git


<h1 style="color:yellow; font-weight:bold;;" >Useful Extensions to install</h1>

Prettier - Code formatter -  Format your code

ESLint  - check your code better cleaner code with certain rules

Prisma - ORM Tool with Database

Simple React Snippets - sfc

Tailwind CSS IntelliSense

JavaScript (ES6) code snippets

<h1 style="color:yellow; font-weight:bold;;" >Create a brand new Application</h1>

```npx create-next-app@latest```



<h1 style="color:yellow; font-weight:bold;;" >Getting Started</h1>

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

<h1 style="color:yellow; font-weight:bold;;" >Configure shadcn-ui and create component</h1>

[Reference link - shadcn-ui ](https://ui.shadcn.com/docs/installation/next)

<h3 style="color:orange; font-weight:bold;;">Initialize ShadCn </h3>



```
npx shadcn@latest init
```
<h3 style="color:orange; font-weight:bold;;">Add Component</h3>

```
npx shadcn@latest add button
npx shadcn@latest add dropdown-menu
npx shadcn@latest add sheet
npx shadcn@latest add card
npx shadcn@latest add label
npx shadcn@latest add input
```

```
npm install next-themes
```

<h3 style="color:orange; font-weight:bold;;">Prisma Setup Command</h3>

```
npm i -D prisma @prisma/client  (INSTALL PRISMA & PRISMA CLIENT)
npx prisma init  (PRISMA INITIALIZATION)


npx prisma generate  (GENERATE CLIENT)
npx prisma migrate dev --name init  (MIGRATE MODEL)

npx tsx ./db/seed (SEED DATABASE)

npx prisma studio  (RUN PRISMA STUDIO TOOL)
```

## Deploy on Vercel

Check out our https://pre-shoes-store.onrender.com for more details.
