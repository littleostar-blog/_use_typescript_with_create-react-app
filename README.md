### _use_typescript_with_create-react-app

---

- react demo list
  - you can download [Compare4 actived](https://github.com/littleostar-blog/littleostar-blog.github.io/tree/master/files) to campare them.
  
  - react use js
    - [react-origin-demo.zip](https://github.com/littleostar-blog/_use_typescript_with_create-react-app/raw/master/demos/react-origin-demo.zip)
  - react use ts
    - [react-origints-demo.zip](https://github.com/littleostar-blog/_use_typescript_with_create-react-app/raw/master/demos/react-origints-demo.zip)
  - react use [create-react-app-typescript](https://github.com/wmonk/create-react-app-typescript/)
    - [react-thirdpartts-demo.zip](https://github.com/littleostar-blog/_use_typescript_with_create-react-app/raw/master/demos/react-thirdpartts-demo.zip)

---

- react create-log
  - react use js
    ```
    PS C:\WebstormProjects> create-react-app react-origin-demo

    Creating a new React app in C:\WebstormProjects\react-origin-demo.

    Installing packages. This might take a couple of minutes.
    Installing react, react-dom, and react-scripts...

    + react@16.6.3
    + react-scripts@2.1.1
    + react-dom@16.6.3
    added 1698 packages from 661 contributors in 83.229s

    Initialized a git repository.

    Success!
    ```
  
  - react use ts
    ```
    PS C:\WebstormProjects> create-react-app react-origints-demo --typescript

    Creating a new React app in C:\WebstormProjects\react-origints-demo.

    Installing packages. This might take a couple of minutes.
    Installing react, react-dom, and react-scripts...

    + react-dom@16.6.3
    + react@16.6.3
    + react-scripts@2.1.1
    + @types/jest@23.3.9
    + @types/react-dom@16.0.9
    + @types/react@16.7.3
    + @types/node@10.12.6
    + typescript@3.1.6
    added 1705 packages from 728 contributors in 145.64s
    We detected TypeScript in your project (src\App.test.tsx) and created a tsconfig.json file for you.

    Your tsconfig.json has been populated with default values.


    Initialized a git repository.

    Success!
    ```
  
  - react use create-react-app-typescript
    ```
    PS C:\WebstormProjects> create-react-app react-thirdpartts-demo --scripts-version=react-scripts-ts

    Creating a new React app in C:\WebstormProjects\react-thirdpartts-demo.

    Installing packages. This might take a couple of minutes.
    Installing react, react-dom, and react-scripts-ts...


    > uglifyjs-webpack-plugin@0.4.6 postinstall C:\WebstormProjects\react-thirdpartts-demo\node_modules\webpack\node_modules\uglifyjs-webpack-plugin
    > node lib/post_install.js

    + react-dom@16.6.3
    + react@16.6.3
    + react-scripts-ts@3.1.0
    added 1400 packages from 733 contributors in 82s
    Installing @types/node, @types/react, @types/react-dom, @types/jest, typescript as dev dependencies npm...

    npm WARN ajv-keywords@3.2.0 requires a peer of ajv@^6.0.0 but none is installed. You must install peer dependencies yourself.
    npm WARN fork-ts-checker-webpack-plugin@0.2.10 requires a peer of typescript@^2.1.0 but none is installed. You must install peer dependencies yourself.
    npm WARN ts-jest@22.0.1 requires a peer of jest@^22.0.1 || ^22.1.0-alpha.1 || ^23.0.0-alpha.1 but none is installed. You must install peer dependencies yourself.
    npm WARN ts-jest@22.0.1 requires a peer of typescript@2.x but none is installed. You must install peer dependencies yourself.
    npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@1.2.4 (node_modules\fsevents):
    npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.4: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"})

    + @types/jest@23.3.9
    + @types/react-dom@16.0.9
    + @types/react@16.7.3
    + @types/node@10.12.6
    + typescript@3.1.6
    added 7 packages from 68 contributors in 13.174s

    Success!
    ```

---

- Solution
  - the node.js version must be 8.10.0 +
  - react use ts

  - ```
    create-react-app my-app --typescript
    ```
    or
  
  - ```
    npx create-react-app my-app --typescript
    ```
    or
    
  - ```
    npm init react-app my-app --typescript
    ```
    or
    
  - ```
    yarn create react-app my-app --typescript
    ```

---

- Reference website
  - https://medium.com/byteconf/getting-started-with-typescript-in-create-react-app-2306b713088f
  - https://vincenttunru.com/migrate-create-react-app-typescript-to-create-react-app/

---

end
