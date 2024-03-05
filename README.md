# Hello there 👋

```typescript
function formatMe() {
  const content = {
    name: "luo xi",
    role: "Frontend Engineer",
    languageSpoken: ['zh_CN', 'en_US'],
  }
  const sayHi = async (text: string) => {
    const msg = await chatgpt(text)
    return msg
  }
}
const me = formatMe()
async(() => {
  const resolveMsg = await me.sayHi("Can you join us?") // resolveMsg = 'of course'
})()

```

## 📝 About Me

- Personal website and blog: https://blog.15weblove.com/

