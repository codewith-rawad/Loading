# ⚡ Animated Loading Indicator

A stunning CSS animation that simulates a **bouncing ball** with smooth squishing and stretching effects! 🚀  

## 🎨 Preview
This animation creates a **realistic bouncing effect** with:  
✔ **Smooth scaling** (squishing & stretching)  
✔ **Shadow for depth**  
✔ **Gradient for a 3D feel**  
✔ **Opacity changes for realism**  

## 🛠️ Technologies Used
- **HTML5**
- **CSS3**
- **Pure Animations (No JavaScript!)**

## 🚀 How It Works
```css
@keyframes move {
    0% { transform: translateY(0) scaleX(1) scaleY(1); opacity: 1; }
    20% { transform: translateY(-70px) scaleX(0.9) scaleY(1.1); opacity: 0.9; }
    40% { transform: translateY(0) scaleX(1.3) scaleY(0.5); opacity: 1; }
    50% { transform: translateY(5px) scaleX(1) scaleY(0.8); opacity: 0.95; }
    60% { transform: translateY(-10px) scaleX(0.95) scaleY(1.05); opacity: 1; }
    80% { transform: translateY(0) scaleX(1.1) scaleY(0.9); opacity: 1; }
    100% { transform: translateY(0) scaleX(1) scaleY(1); opacity: 1; }
}
