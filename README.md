## Ecommerce Fullstack Application 

## Technologies 
1. NEXT.js
2. React.js 
3. Sanity
4. Clerk for Authentication
5. TypeScript
6. Shadcn
7. Tailwind CSS
8. Routing
9. Headless CMS
10. Stripe for Payment 
11. Framer Motion for Animations

####  npx create-next-app@latest ecommerce-application
####  npm create sanity@latest -- --project 0fm8ezgg --dataset production --template clean --typescript --output-path studio-ecommerce
#### npm install --save-dev @types/hast @types/react-is @types/unist @types/which


## .env.local file 
Declared projectid code for sanity and studio also

## SETUP
1. setup the sanity studio
2. setup clerk
3.  - created middleware .ts to integrate clerk in the app
    - import cleark provider in layout.tsx
    - move layout.tsx in created folder (store)
    - and create a layout .tsx in studio to seperat ethe backedn and frontend
    - moved page.tsx into store folder
    - remove the bydefault code to setup the project like divs and classnames
4. Started with header component
5. imported signinbutton from clerk -redirect to clerk hosted sign-in page by default

##### Working on this Project
