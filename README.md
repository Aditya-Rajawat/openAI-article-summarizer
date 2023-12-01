# *OpenAI-Article-Summarizer*

- *Integrated GPT-4 application which simplifies reading by transforming lengthy articles into clear and concise summaries. Features included are integration with RTK, clipboard copying, and storing browsing history.*

- *Live Link : https://articlesummarizeropenai.netlify.app/*

- *Tech Stack : ReactJS, Redux Toolkit, Tailwind CSS*

# *Setup of the project*

- Create react app with vite :
 ```
  npm create vite@latest
  ```

- Install tailwindcss via npm, and create your tailwind.config.js file :
```
npm install -D tailwindcss
npx tailwindcss init
```
- Configure your template paths
```
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./src/**/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

