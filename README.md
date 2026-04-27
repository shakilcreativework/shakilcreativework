<!-- 🔥 Banner -->
![Banner](https://i.ibb.co.com/RpYvrg4x/arts-5.jpg)

# 👋 Hi, I'm Md Shakil Ahmed
### 💻 Frontend Developer | MERN Stack Developer (Learner)

📍 Sirajgonj, Bangladesh  
📧 shakilcreativework@gmail.com  

---

## 🧠 About Me
I am a passionate web developer focused on building modern, responsive, and user-friendly web applications.  
Currently, I am learning full-stack development and working on real-world projects to improve my skills and create impactful digital products.

---

## 🚀 What I'm Doing

- 🔭 I’m currently working on a scalable Free & Premium Vector / Design Resource Platform  
- 🌱 I’m diving deep into React, Next.js, and full-stack development (Node.js, MongoDB)  
- 👯 I’m open to collaborating on frontend or MERN stack projects  
- 🤔 I’m seeking guidance on backend architecture and scalable application design  
- 💬 Ask me about HTML, CSS, Tailwind, JavaScript, React, and modern UI development  
- 📫 Reach me at: shakilcreativework@gmail.com  
- 😄 Pronouns: He/Him  
- ⚡ Fun fact: I enjoy turning simple ideas into real-world products that people actually use 🚀  

---

## ⚡ Skills

### 🎨 Frontend
<p>
  <img src="https://skillicons.dev/icons?i=html,css,tailwind,js,react,nextjs" />
</p>

### ⚙️ Backend
<p>
  <img src="https://skillicons.dev/icons?i=nodejs,express,mongodb,firebase" />
</p>

### 🛠 Tools
<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode" />
</p>

---

## 🌐 Connect With Me
<p>
  <a href="YOUR_LINKEDIN">LinkedIn</a> |
  <a href="YOUR_FACEBOOK">Facebook</a> |
  <a href="YOUR_DISCORD">Discord</a>
</p>

---

## 📊 GitHub Stats

![Shakil's GitHub stats](https://github-readme-stats.vercel.app/api?username=shakilcreativework&show_icons=true&theme=radical)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=shakilcreativework&layout=compact&theme=radical)

![GitHub Streak](https://streak-stats.demolab.com?user=shakilcreativework&theme=radical)

---

## 🏆 Achievements

- 🎓 Completed Web Development Course (Batch 07)  
- 🚀 Currently continuing Batch 13  
- 💻 Building real-world full-stack projects  

---

## 📌 Featured Project

# 🧲 MagneticButton Component

A reusable React button component with a smooth **magnetic hover effect**, built using **React**, **Tailwind CSS**, and **clsx**.

---

## ✨ Features

* 🧲 Magnetic hover interaction
* 🎨 Fully customizable with `className`
* 🔗 Supports:

  * Button
  * Internal routing (`react-router-dom`)
  * External links
* ⚡ Lightweight and reusable
* 🎯 Smart default styles (auto background & text)

---

## 📦 Installation

Make sure you have these installed:

```bash
npm install clsx react-router-dom
```

---

## 🚀 Usage

### 1. Import Component

```jsx
import MagneticButton from "./MagneticButton";
```

---

### 2. Basic Button

```jsx
<MagneticButton text="Click Me" />
```

---

### 3. With Children (Recommended)

```jsx
<MagneticButton>
  Click Me 🚀
</MagneticButton>
```

---

### 4. Custom Styling

```jsx
<MagneticButton className="bg-amber-300 text-xl hover:scale-105">
  Custom Button
</MagneticButton>
```

---

### 5. React Router Link

```jsx
<MagneticButton to="/about" as="link">
  Go to About
</MagneticButton>
```

---

### 6. External Link

```jsx
<MagneticButton href="https://google.com" as="a">
  Open Google
</MagneticButton>
```

---

### 7. Click Handler

```jsx
<MagneticButton onClick={() => alert("Clicked!")}>
  Click Action
</MagneticButton>
```

---

## ⚙️ Props

| Prop        | Type     | Description                           |
| ----------- | -------- | ------------------------------------- |
| `children`  | node     | Custom content inside button          |
| `text`      | string   | Alternative to children               |
| `className` | string   | Custom Tailwind classes               |
| `to`        | string   | Route path (for React Router)         |
| `href`      | string   | External link                         |
| `onClick`   | function | Click handler                         |
| `as`        | string   | `"button"` (default), `"link"`, `"a"` |

---

## 🎨 Default Styles

* `inline-flex` layout
* `rounded-full`
* `shadow-xs` → `hover:shadow-sm`
* `transition-transform`
* Default:

  * `bg-white` (if no bg provided)
  * `text-black` (if no text color provided)

---

## ⚠️ Important Notes

### 1. React Router Setup

Wrap your app with:

```jsx
import { BrowserRouter } from "react-router-dom";

<BrowserRouter>
  <App />
</BrowserRouter>
```

---

### 2. Tailwind Shadow

`shadow-xs` is **not default** in Tailwind.

Add this to your `tailwind.config.js`:

```js
theme: {
  extend: {
    boxShadow: {
      xs: "0 1px 2px rgba(0,0,0,0.05)",
    },
  },
},
```

---

### 3. Class Override Behavior

You can override defaults:

```jsx
<MagneticButton className="bg-red-500 text-white">
  Override Style
</MagneticButton>
```

---

## 🧠 How It Works

* Tracks mouse position inside the button
* Applies `transform: translate()` for magnetic effect
* Resets on mouse leave
* Uses `useRef` + `useEffect`

---

## 📁 File Structure

```
/components
  └── MagneticButton.jsx
```

---

## 💡 Future Improvements

* Variants (`primary`, `outline`, `ghost`)
* Sizes (`sm`, `md`, `lg`)
* Disable magnetic effect on mobile
* Glow / gradient effects

---

## 🧑‍💻 Author

Made with ❤️ using React + Tailwind

---

## 📄 License

Free to use and modify.


---

## ⚡ Focus

Building real-world projects, improving problem-solving skills, and becoming a professional full-stack developer 🚀
