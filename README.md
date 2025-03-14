# 📝 Display Full Name

## 📌 About
This is a simple JavaScript project that dynamically displays a full name inside a `<p>` element on a webpage.

## 📂 Project Structure
- `index.html` - The main HTML file with a paragraph element to display the name.
- `script.js` - A JavaScript file that concatenates the first and last name and updates the HTML content.

## 📝 Code
### 📄 index.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Display Full Name JS</title>
</head>
<body>
  <p id="demo"></p>
  <script src="script.js"></script>
</body>
</html>
```

### 📜 script.js
```javascript
let firstName = 'Goga';
let lastName = 'Gabelia';
const fullName = firstName + ' ' + lastName;

document.getElementById('demo').innerHTML = fullName;
```

## 🚀 Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/your-repo-name.git
   ```
2. Navigate to the project folder:
   ```sh
   cd your-repo-name
   ```
3. Open `index.html` in a browser to see the full name displayed.

## 🎯 Features
- Uses JavaScript to modify the DOM dynamically.
- Demonstrates string concatenation.
- Simple and beginner-friendly.

## 👨‍💻 Author
**Goga Gabelia** - Software Developer

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).
