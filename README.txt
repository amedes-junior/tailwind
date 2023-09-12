touch styles.css

mkdir src

touch src/index.html

npm install -D tailwindcss

npx tailwindcss init

/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./src/**/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
}

@tailwind base;
@tailwind components;
@tailwind utilities;

npx tailwindcss -i styles.css -o ./src/css/styles.css --watch


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Title</title>
  <link rel="stylesheet" href="css/styles.css">
</head>
<body>
</body>
</html>


Instalação Fonts Awesome: cdnjs.com