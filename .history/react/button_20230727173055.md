---
title: Button
type: snippet
language: react
tags: [css, tailwindcss, jsx]
cover: image
dateModified: 2023-07-23
---

<!-- describe component -->

Button component
- 


```tsx
interface ButtonProps {
    children: React.ReactNode;
    buttonType: "button" | "submit" | "reset";
    name: string;
    disabled?: boolean;
}

const Button = ({ children, buttonType, name, disabled }: ButtonProps) => {
    return <button
        disabled={disabled}
        name={name} type={buttonType} className="bg-blue-500 text-white font-medium text-lg py-3 px-6 hover:bg-blue-600 duration-200 ease-linear drop-shadow-lg rounded-lg active:drop-shadow-sm">
        {children}
    </button>
}

export default Button;
```

```jsx
ReactDOM.createRoot(document.getElementById('root')).render(
  <ComponentName />
);
```