# Miscellaneous functions

Some markdown versions supports emojis using the colons, using ":smile:" and it gives "😊".

In markdown It's possible to do inline code making the font monospaced, like: `const x = 0;`
This is made using backticks `.

It's also important to notice that the backticks when combined three times, It's possible to make code blocks. Like this:

```
const block = "That is a simple code block.";
```

You can even specify the language that you're using by just putting the extension of your language after the initial three backticks. Providing proper syntax highlighting.

```js
const block = {
  type: "code block",
  lang: "js"
};
```

It's possible to just ident a few times to make a block of code, like that:

    const hello = "World";

It's most preferable to use triple backticks, because is cleaner. 