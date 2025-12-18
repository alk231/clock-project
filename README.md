# Analog Clock ⏰

A beautiful, working analog clock built with vanilla HTML, CSS, and JavaScript. Watch the hands move in real-time as they track the current time from your system.

## 🏽 Features

- **Real-Time Display**: The clock updates every second to show the current time.
- **Animated Hands**: Three hands (hour, minute, and second) rotate smoothly to indicate time.
- **Color-Coded Hands**:
  - Red hand for hours
  - Blue hand for minutes
  - White hand for seconds
- **Numbered Dial**: Numbers 1-12 are positioned around the clock face.
- **Responsive Design**: Looks good on different screen sizes.

## 🛠️ Tech Stack

- **HTML5**: For the clock structure and dial numbers.
- **CSS3**: For styling, positioning, and animations.
- **JavaScript**: For real-time calculations and hand rotations.

## 🚀 How It Works

1. JavaScript retrieves the current time using `new Date()`.
2. Calculates the rotation angle for each hand based on hours, minutes, and seconds.
3. Applies CSS transforms to rotate the hands to the correct positions.
4. Updates every second using `setInterval()`.

### Rotation Calculations

- **Hour Hand**: Rotates 30 degrees per hour (360° ÷ 12 hours) + additional rotation for minutes.
- **Minute Hand**: Rotates 6 degrees per minute (360° ÷ 60 minutes).
- **Second Hand**: Rotates 6 degrees per second (360° ÷ 60 seconds).

## 📂 Project Structure

- `index.html`: Clock markup with hand elements and dial numbers.
- `style.css`: Styling for the clock face, hands, and overall layout.
- `script.js`: JavaScript logic for time calculations and hand rotation.

## 🏃 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/alk231/clock-project.git
   ```

2. **Open in browser**
   - Navigate to the project folder.
   - Open `index.html` in any modern web browser.
   - Watch the clock tick!

## 🧐 Learning Value

This project is great for learning:
- DOM manipulation with JavaScript
- CSS transforms and rotations
- Real-time calculations based on system time
- Working with the `Date` object
- Using `setInterval()` for continuous updates

## 👤 Author

**Alok Kumar**
- GitHub: [@alk231](https://github.com/alk231)

---
*Tick tock, made with ❤️ and JavaScript.*
