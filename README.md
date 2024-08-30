
# Vintage Countdown Timer

A visually appealing countdown timer application with a vintage theme, built using Flask for the backend and HTML, CSS, and JavaScript for the frontend. The timer displays large countdown numbers, allows time adjustments, and plays a sound when the countdown finishes.

## **Project Structure**

```
countdown_app/
│
├── backend/
│   ├── app.py                 # Flask backend server
│   ├── static/
│   │   ├── vintage_style.css  # CSS file for styling the frontend
│   │   └── alarm.mp3          # Audio file played when countdown ends
│   └── templates/
│       └── index.html         # Main HTML file
│
└── README.md                  # Documentation file
```

## **Features**

- **Vintage Theme**: Dark background with gold text, reminiscent of old-school displays.
- **Adjustable Countdown**: Set the countdown time manually using input or increase/decrease buttons.
- **Sound Alert**: Plays a sound when the countdown ends.
- **Interactive UI**: Start and restart the countdown with a simple button click.

## **Getting Started**

### **Prerequisites**

- Python 3.x installed on your system.
- Flask installed. If not already installed, you can install it using:

  ```bash
  pip install flask
  ```

### **Installation**

1. **Clone the Repository**:
   
   ```bash
   git clone <repository-url>
   cd countdown_app/backend
   ```

2. **Run the Flask Application**:

   ```bash
   python app.py
   ```

3. **Access the Application**:

   Open your web browser and navigate to:

   ```
   http://127.0.0.1:5000
   ```

## **Usage**

1. **Adjust the Countdown Time**:
   - Use the `+` and `-` buttons to increase or decrease the time.
   - Alternatively, enter the desired time directly into the input field.

2. **Start the Countdown**:
   - Click the **Start Countdown** button. The countdown will begin immediately.
   - The display shows the time in `MM:SS` format.

3. **Sound Alert**:
   - When the countdown reaches zero, a sound will play to alert you that the time is up.

4. **Restarting**:
   - Click the **Restart Countdown** button to reset and start the timer again.

## **Troubleshooting**

- **Sound Not Playing**: Ensure the browser permissions allow audio playback. If the issue persists, check that the sound file (`alarm.mp3`) is correctly placed in the `static` folder.
- **Error Messages**: Use the browser console (`F12` in most browsers) to inspect any JavaScript errors that might be affecting functionality.

## **Customization**

- **Change the Sound**: Replace `alarm.mp3` in the `static` folder with any sound of your choice, ensuring the file name remains the same or update the path in `index.html`.
- **Modify the Design**: Edit `vintage_style.css` to adjust the colors, font, and overall look to suit your preferences.

## **Future Enhancements**

- Add more sound options and themes.
- Include a countdown history log.
- Add mobile responsiveness.

## **Contributing**

1. Fork the repository.
2. Create your feature branch: `git checkout -b feature/YourFeature`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/YourFeature`.
5. Open a pull request.

## **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## **Acknowledgments**

- I would like to thank everyone who reaches out to exchange ideas. Your feedback and suggestions are highly valued!
- Feel free to contact me on [LinkedIn](https://www.linkedin.com/in/ivana-osmajlic/) for any discussions or collaborations.
