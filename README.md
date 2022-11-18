<!--
**Carina957/Carina957** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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

### Hi there 👋, I'm Carina. 😜

- 🔭 I’m currently working on Hangzhou. ⌨

- 🎞 I like listening to music and watching movies. 🎧

- 🎇 Like to make new friends. ✨

- 🎠 My tech stack is Vue JavaScript and TypeScript. 🎡

- 💬 Be free to ask me about anything [here](https://www.baidu.com/). 🕶

#### 🎉 In the end, I wish you a salary of **20K** 🎉🎉🎉

[![Alva's github stats](https://github-readme-stats.vercel.app/api?username=Carina957)](https://github.com/Carina957/github-readme-stats)

<details><summary><b>Show instructions</b></summary>

1. Install the preset:

    ```sh
    $ npm install --save-dev size-limit @size-limit/file
    ```

2. Add the `size-limit` section and the `size` script to your `package.json`:

    ```diff
    + "size-limit": [
    +   {
    +     "path": "dist/app-*.js"
    +   }
    + ],
      "scripts": {
        "build": "webpack ./webpack.config.js",
    +   "size": "npm run build && size-limit",
        "test": "jest && eslint ."
      }
    ```

3. Here’s how you can get the size for your current project:

    ```sh
    $ npm run size
      Package size: 30.08 kB with all dependencies, minified and gzipped
    ```

4. Now, let’s set the limit. Add 25% to the current total size and use that as
   the limit in your `package.json`:

    ```diff
      "size-limit": [
        {
    +     "limit": "35 kB",
          "path": "dist/app-*.js"
        }
      ],
    ```

5. Add the `size` script to your test suite:

    ```diff
      "scripts": {
        "build": "webpack ./webpack.config.js",
        "size": "npm run build && size-limit",
    -   "test": "jest && eslint ."
    +   "test": "jest && eslint . && npm run size"
      }
    ```



6. Git order
    
    - Git modify user name mailbox
    
    ``` sh
    $ git config --global user.name "name"
    $ git config --global user.email "email"
    ```
    
    - Git view global configuration
    
    ``` sh
    $ git config --global --list
    ```

</details>


<!-- ![logo](https://img-blog.csdnimg.cn/img_convert/25872bc833a652abad37509dc1cc4514.png 'Github') -->

<!-- <img src="https://img-blog.csdnimg.cn/img_convert/25872bc833a652abad37509dc1cc4514.png" alt="Logo" width="100%" align="right"> -->
<img src="https://raw.githubusercontent.com/likaia/likaia/main/code.gif" alt="Logo" width="450" align="right">
