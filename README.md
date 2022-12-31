# curso-gratuito-tailwind2

## Objetivo: 
Aprender o framework Tailwind

## Youtube Playlist <br>
https://www.youtube.com/playlist?list=PLcoYAcR89n-r1m-tMfV4qndrRWpT_rb9u

## Links Importantes

Pagina do tailwind <br>
https://tailwindcss.com/

Pagina Oficial Instalação do Tailwind <br>
https://tailwindcss.com/docs/installation


## Comandos usados na Instalação

npm install -D tailwindcss <br>
npx tailwindcss init <br>

No arquivo tailwind.config.js modificar a linha <br>
content: ["./src/**/*.{html,js}"], <br>

Criar o arquivo src/input.css <br>

@tailwind base; <br>
@tailwind components; <br>
@tailwind utilities; <br>

npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch


