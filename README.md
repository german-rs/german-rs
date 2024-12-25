```javascript
(() => {
    class Person{
        constructor() {
            this.username = 'german-rs';
            this.name = 'Germán Riveros';
            this.email = 'contacto@germanriveros.cl';
            this.web = 'https://germanriveros.cl';
            this.linkedin = 'https://www.linkedin.com/in/german-rs/';
            this.FreeCodeCamp = 'https://www.freecodecamp.org/german-rs';
            this.code = {
                llms: ['Copilot', 'chatGPT', 'Claude', 'Gemini', 'Leonardo', 'Ideogram'],
                languages: ['JavaScript', 'Dart'],
                frontend: ['VueJS', 'Sass', 'Gutenberg', 'Bootstrap', 'jQuery'],
                mobile: ['Flutter'],
                backend: ['NodeJS'],
                database: ['PostgreSQL', 'MySQL', 'SQLite3'],
                tools: ['GIT', 'GitHub'],
                misc: ['Firebase', 'Figma', 'Inkscape', 'WordPress'];
            };
        }
        toString() {
            return `${this.name} | ${this.email}`;
        }
    }
    const me = new Person();
    console.log(me.toString());
})();        
```

<!--
**german-rs/german-rs** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
