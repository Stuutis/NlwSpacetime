- Back
  npm init -y
  npm i typescript -D
  npm i @types/node -D

npm i prisma -D
npx prisma init --datasource-provider SQLite
npx prisma migrate dev
npx prisma studio

npm i @prisma/client

- Front
  npx create-next-app@latest NOME --use-npm

npm i prettier-plugin-tailwindcss -D

- Mobile
  npx create-expo-app mobile
  npx expo start
  npm i nativewind
  npm i tailwindcss -D
  npx taildwindcss init
  npm i eslint @rocketseat/eslint-config -D
  npm i prettier-plugin-tailwindcss -D
