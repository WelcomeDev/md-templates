# React Context

## Что такое
Крутая штука. [Ссылка](https://github.com/WelcomeDev/md-templates)

## Использование через хук

Чтобы каждый раз не импортировать `useContext` и  необходимый объект контекста, мы можем использовать кастомный хук и использовать этот контекст проще:
```typescript jsx
function useThemeContext() {
  const theme = useContext(ThemeContext);
  if(!theme) throw new Error("useThemeContext can't be used outside of ThemeContext provider");
  return theme;
}
```

Списочек
- раз
- два
- три
- [еще ссылка](https://habr.com/ru/post/465507/)

Просто параграф. Ага
