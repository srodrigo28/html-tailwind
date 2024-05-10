
Link
  ```
  https://www.youtube.com/watch?v=rjXXDv23-6Y
  ```

#### Dependências
npm install -D tailwindcss
npx tailwindcss init

#### CSS Base config
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

#### Tailwind Config
```
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./**/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

#### Script para rodar package.json
```
"dev": "npx tailwindcss -i ./css/style.css -o ./css/output.css --watch"
```

usar o live server
