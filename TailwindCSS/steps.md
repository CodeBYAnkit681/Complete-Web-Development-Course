## HOW TO SETUP A TAILWIND CSS 

STEP 1 : INSTALL AND INITIATE TAILWIND CSS
```
npm install tailwindcss @tailwindcss/cli
```

STEP 2 : Import Tailwind in your CSS Main file e.g (src/input.css)
```
@import "tailwindcss";
```

STEP 3 : Start the Tailwind CLI build process by input and making output files

```
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
```

STEP 4 : Link your output.css in your html file 
```
<link href="./output.css" rel="stylesheet">
```