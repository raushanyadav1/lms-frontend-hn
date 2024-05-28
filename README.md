# lms frontend

### setup instruction

1. clone the project 
...
git clone https://github.com/raushanyadav1/lms-frontend-hn.git
...

2. move into the directory
...
cd lms-frontend
...

3. install dependencies
...
npm i
...

4. run the server
...
npm run dev
...

### setup instructions for tailwind
[tailwind officiall instruction doc] (https://tailwindcss.com/docs/installation)

1. install taillwindcss
...
npm install -D tailwindcss
...

2. create tailwind config file
...
npx tailwindcss init
...

3. add file extention to tailwind config fille in the content property

...
"./src/**/*.{html,js,jsx,ts,tsx}"
...

4. add the tailwind directives at the top of the 'index.css' 

...

@tailwind base;
@tailwind components;
@tailwind utilities;
...

### adding plugins and dependencies
...

 npm install @reduxjs/toolkit react-redux react-router-dom react-icons react-chartjs-2 chart.js daisyui    axi
os react-hot-toast @tailwindcss/line-clamp

...

### Configure auto import sort esline

1. Install simple import sore

```
    npm i -D eslint-plugin-simple-import-sort
```

2. Add rule in `.eslint.cjs`

```
    'simple-import-sort/imports': 'error'
```

3. add simple-import sort plugin in `.eslint.cjs`

```
    plugins: [..., 'simple-import-sort']
```

4. To enable auto import sort on file save in vscode

    - Open `settings.json`
    - add the following config
```
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true
    }
```
 

