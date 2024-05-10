
#### Link projeto
  ```
  https://www.youtube.com/watch?v=rjXXDv23-6Y
  ```
#### CDN Tailwind
  ```
  https://tailwindcss.com/docs/installation/play-cdn  
  ```

  ```
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
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
