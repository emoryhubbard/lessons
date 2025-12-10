### Why use one class per element? ("Laser" styling vs. "Grenade" styling)

Using individual classes like `.card`, `.title`, and `.text` lets us style each element precisely — a **laser** — instead of one rule accidentally affecting everything — a **grenade**.

**index.html**
```html
<div class="card">
  <h2 class="title">Dashboard</h2>
  <p class="text">Welcome back!</p>
</div>
```

**index.css**
```css
.card {
  background: white;
  padding: 24px;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

.title {
  font-size: 1.5rem;
  font-weight: 600;
}

.text {
  font-size: 1rem;
  color: #4b5563;
}
```