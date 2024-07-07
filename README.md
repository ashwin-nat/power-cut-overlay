
# ⚡ Power-Cut Overlay

> "Because even when the lights go out, the show must go on!"

Welcome to the Power-Cut Overlay project! This is your one-stop solution for tracking the time since your last power cut, all while adding some pizazz to your stream. Who knew power outages could be so entertaining?

## 🛠️ Setup

Before we dive into the fun, let’s get you set up. Follow these steps to become the proud owner of a Power-Cut Overlay:

### Prerequisites

1. **Python 3.x** - Because Python 2.7 is so last decade.
2. **Virtual Environment** - Keep it clean, folks!
3. **Unix-based system** - Sorry Windows users, this party is exclusive!

### Installation

1. **Clone this repo** (or just download it, we’re not picky):
   ```sh
   git clone https://github.com/yourusername/power-cut-overlay.git
   cd power-cut-overlay
   ```

2. **Create a virtual environment** (for those who like it clean):
   ```sh
   python3 -m venv venv
   ```

3. **Activate the virtual environment**:
   ```sh
   source venv/bin/activate
   ```

4. **Install the dependencies** (it's like feeding your project its favorite snacks):
   ```sh
   pip install Flask Flask-SocketIO eventlet
   ```

5. **Run the app**:
   ```sh
   python app.py
   ```

6. **Open your browser** and navigate to `http://127.0.0.1:5000`. Behold the glory of your power-cut timer!

## 🖥️ Frontend

Your frontend is a snazzy HTML file that displays the time since the last power cut in all its glory.

## 🧠 How It Works

### Backend (aka The Brains)

Your backend is powered by a Flask app that calculates the time since the last power cut and uses Socket.IO to update the frontend in real-time. Fancy, right?

### Running the Show

When you start the Flask app, it continuously calculates the time difference since the last power cut and broadcasts this vital information to your frontend. So, you and your audience are always in the loop!

## 🤔 Why?

Because knowing the exact time since your last power cut adds that extra sprinkle of excitement to your stream. Plus, it's a cool way to show off your coding skills!

## 🧟 Need Help?

Got issues? Feel free to open an issue, or just scream into the void. Either way, we're here to help (well, sort of).

## 🥳 Contributing

Want to add more fun features? Fork this repo and send us a pull request. We promise to review it between power cuts.

## 🙌 Credits

Special thanks to [**Ashvin Panicker**](https://github.com/ashvinpanicker) for the UI design. Your design skills are electrifying!

---

May your streams be uninterrupted and your timers accurate! Happy coding! ⚡🎉

---