- Create a folder named threads
- Open vs code
- Drag n drop it on vs code
- Open terminal on vs code using - ctrl+`
- Now type command 

  npx create-next-app@latest ./

![](Aspose.Words.6693753a-0029-41ca-8994-878ea9f8b9ca.001.png)

- Follow above steps for what to install


- Type Command 
- npm install @clerk/nextjs
- ![](Aspose.Words.6693753a-0029-41ca-8994-878ea9f8b9ca.002.png)<https://clerk.com/>
- What is clerk?
- More than authentication, clerk is more than a "sign-in box." Integrate complete user management UIs and APIs, purpose-built for React, Next.js, and the Modern Web.


(we are going to use its full potential more than just AUTH page)

- Follow Documentation <https://clerk.com/docs>
- Package required

  npm install @uploadthing/react mongoose svix uploadthing

- ![](Aspose.Words.6693753a-0029-41ca-8994-878ea9f8b9ca.003.png)Folder tree

















- Run command

  npm run dev

![](Aspose.Words.6693753a-0029-41ca-8994-878ea9f8b9ca.004.png)

- Run npm dev after editing  page.tsx and global.css
- Config through tailwind.config.js
- Run npm run dev 

  ![](Aspose.Words.6693753a-0029-41ca-8994-878ea9f8b9ca.005.png)

- To fix this error we are going to installsome tailwindcss- animate

  npm install tailwindcss-animate

- Fixed this issue

  ![](Aspose.Words.6693753a-0029-41ca-8994-878ea9f8b9ca.006.png)









- <https://nextjs.org/docs/app/building-your-application/routing/route-groups>

  **Route Groups**

In the app directory, nested folders are normally mapped to URL paths. However, you can mark a folder as a Route Group to prevent the folder from being included in the route's URL path.

This allows you to organize your route segments and project files into logical groups without affecting the URL path structure.

Route groups are useful for:

Organizing routes into groups e.g. by site section, intent, or team.

1. Enabling nested layouts in the same route segment level:
1. Creating multiple nested layouts in the same segment, including multiple root layouts
1. Adding a layout to a subset of routes in a common segment
- Follow these Documentation

