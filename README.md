### Install Tailwind CSS
```
npm install tailwindcss @tailwindcss/cli
```
###  Import Tailwind in your CSS src/input.css
``` 
@import "tailwindcss";
```
### Start the Tailwind CLI build process .add this in script as build  then in terminal npm run build
```
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
```
### Start using Tailwind in your HTML in src/input.css