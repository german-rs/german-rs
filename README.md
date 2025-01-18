```
      ___           ___           ___       ___       ___     
     /\__\         /\  \         /\__\     /\__\     /\  \    
    /:/  /        /::\  \       /:/  /    /:/  /    /::\  \   
   /:/__/        /:/\:\  \     /:/  /    /:/  /    /:/\:\  \  
  /::\  \ ___   /::\~\:\  \   /:/  /    /:/  /    /:/  \:\  \ 
 /:/\:\  /\__\ /:/\:\ \:\__\ /:/__/    /:/__/    /:/__/ \:\__\
 \/__\:\/:/  / \:\~\:\ \/__/ \:\  \    \:\  \    \:\  \ /:/  /
      \::/  /   \:\ \:\__\    \:\  \    \:\  \    \:\  /:/  / 
      /:/  /     \:\ \/__/     \:\  \    \:\  \    \:\/:/  /  
     /:/  /       \:\__\        \:\__\    \:\__\    \::/  /   
     \/__/         \/__/         \/__/     \/__/     \/__/    
```


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
            this.technologies = {
                llms: ['Copilot', 'chatGPT', 'Claude', 'Gemini', 'Cohere', 'DeepSeek'],
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
