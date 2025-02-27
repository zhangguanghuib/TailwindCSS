# React + TailwindCSS4

## Step 1: Create React Project via Vite:<br/>
```ps
npm create vite@latest ReactTailwindCss4 -- --template react
```
![image](https://github.com/user-attachments/assets/ce2b2ca4-90ec-4dbc-8e4c-d729cd17be2d)

## Step 2: Go to https://tailwindcss.com/docs/installation/using-vite<br/>
```
npm install tailwindcss @tailwindcss/vite
```
## Step 3:
```
import { defineConfig } from 'vite'
import tailwindcss from '@tailwindcss/vite'
export default defineConfig({
  plugins: [
    tailwindcss(),
  ],
})
```
![image](https://github.com/user-attachments/assets/d4847fb0-2064-4a6d-b17a-e2e21266b0e0)

## Step 4:
```ps
@import "tailwindcss";
```
![image](https://github.com/user-attachments/assets/269b42be-d987-42c1-8582-bd76338b58d6)

## Step 5:
```ps
npm run dev
```
## Step 6:
![image](https://github.com/user-attachments/assets/6feb3e8d-6dec-4d6d-8a3c-2d82ce6e0a55)<br/>
![image](https://github.com/user-attachments/assets/77974f68-cb30-4ffe-9f9c-ea2cfc9b1d00)


