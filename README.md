## ❤️ Lovely

#**FrontEnd** #DesignSystem #*Blockchain*

## 🚀 EXPerience

[![JavaScript](https://img.shields.io/badge/JavsScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=222)](https://github.com/StyleList94?tab=repositories&language=javascript)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=TypeScript&logoColor=eee)](https://github.com/StyleList94?tab=repositories&language=typescript)
[![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=222)](https://github.com/StyleList94?tab=repositories&q=react)
[![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=Next.js&logoColor=eee)](https://github.com/StyleList94?tab=repositories&q=nextjs)
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=Vite&logoColor=f6cf4b)](https://github.com/StyleList94?tab=repositories&q=vite)
[![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=Vitest&logoColor=f6cf4b)](https://github.com/StyleList94?tab=repositories&q=vitest)
[![tailwindcss](https://img.shields.io/badge/tailwindcss-06B6D4?style=flat-square&logo=Tailwind%20CSS&logoColor=eee)](https://github.com/StyleList94?tab=repositories&q=tailwindcss)
[![Storybook](https://img.shields.io/badge/Storybook-FF4785?style=flat-square&logo=Storybook&logoColor=eee)](https://github.com/StyleList94?tab=repositories&q=storybook)
[![Webpack](https://img.shields.io/badge/Webpack-8DD6F9?style=flat-square&logo=Webpack&logoColor=222)](https://github.com/StyleList94?tab=repositories&q=webpack)
[![rollup.js](https://img.shields.io/badge/rollup.js-EC4A3F?style=flat-square&logo=rollup.js&logoColor=eee)](https://github.com/StyleList94?tab=repositories&q=rollupjs)
[![React Native](https://img.shields.io/badge/React%20Native-61DAFB?style=flat-square&logo=React&logoColor=222)](https://github.com/StyleList94?tab=repositories&q=react-native)
[![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=Vercel&logoColor=eee)](https://github.com/StyleList94?tab=repositories&q=vercel)
[![Cloudflare Pages](https://img.shields.io/badge/Pages-F38020?style=flat-square&logo=Cloudflare%20Pages&logoColor=eee)](https://github.com/StyleList94?tab=repositories&q=cloudflare-pages)

## Introduce

```tsx
import React from 'react'

export default function WhoAmI() {
  const [sexuality] = React.useState('man');

  const [framework] = React.useState(['Next.js', 'Vite']);
  const [styling] = React.useState([
    'tailwindcss',
    'styled-components',
    'SCSS',
    'CSS Module',
  ]);
  const [testing] = React.useState(['vitest', 'jest', 'testing-library']);
  const [stateManagement] = React.useState(['redux', 'zustand', 'recoil']);

  return (
    <section>
      <h2>Who am I?</h2>
        
      <h3>Sexuality</h3>
      <p>{sexuality}</p>
        
      <h3>Main Framework</h3>
      <p>{framework[0]}</p>
        
      <h3>Favorite Styling Techniques</h3>
      <p>{styling[0]}</p>
        
      <h3>DOM Testing</h3>
      <ul>
        {testing
          .filter((tool) => tool !== 'jest')
          .map((currentUsed) => (
            <li>{currentUsed}</li>
          ))}
      </ul>
        
      <h3>State Management</h3>
      <ul>
        {stateManagement.slice(0, 2).map((currentUsed) => (
          <li>{currentUsed}</li>
        ))}
      </ul>
    </section>
  );
}
```

<!--
**LovelyHaRa/LovelyHaRa** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

-->
