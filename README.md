# create-svelte

I created this project using;

```bash
pnpm create svelte@latest .

pnpm dlx svelte-add@latest tailwindcss

#Using svelte-add setup tailwind for this project

pnpm isntall

git add . && git commit -m "after installs" && git push origin main

pnpm dev -- --host=10.10.4.41  #ip address is specific to the development server.

pnpm dlx shadcn-svelte@latest init
```

```
✔ Running this command will install dependencies and overwrite your existing tailwind.config.[cjs|js|ts] & app.pcss file. Proceed? … yes
✔ Which style would you like to use? › New York
✔ Which color would you like to use as base color? › Neutral
✔ Where is your global CSS file? … src/app.pcss
✔ Where is your tailwind.config.[cjs|js|ts] located? … tailwind.config.cjs
✔ Configure the import alias for components: … $lib/components
✔ Configure the import alias for utils: … $lib/utils
✔ Write configuration to components.json. Proceed? … yes
Your tailwind.config.cjs has been renamed to tailwind.config.js.
```


Notes from Lawal's clones on YouTube.

```bash
#youtube clone
pnpm create svelte@latest youtube-clone
pnpm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p

```