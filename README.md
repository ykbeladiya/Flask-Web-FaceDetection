# Flask Web Face Detection

A real-time face and eye detection web application built with Flask and OpenCV. This application uses your webcam to detect faces and eyes in real-time through a web interface.

## Features

- Real-time face detection
- Real-time eye detection
- Web-based interface
- Webcam integration
- Live video streaming

## Technologies Used

- Python 3.x
- Flask (Web Framework)
- OpenCV (Computer Vision)
- Haar Cascade Classifiers
- HTML/CSS

## Prerequisites

Before running this project, make sure you have the following installed:
- Python 3.x
- pip (Python package manager)
- Webcam (built-in or external)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/ykbeladiya/Flask-Web-FaceDetection.git
cd Flask-Web-FaceDetection
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

## Usage

1. Run the application:
```bash
python app.py
```

2. Open your web browser and navigate to:
```
http://localhost:5000
```

3. Allow the browser to access your webcam when prompted.

4. The application will start detecting faces and eyes in real-time.

## Project Structure

```
Flask-Web-FaceDetection/
├── app.py                 # Main application file
├── requirements.txt       # Project dependencies
├── Haarcascades/         # Directory containing cascade classifiers
│   ├── haarcascade_frontalface_default.xml
│   └── haarcascade_eye.xml
└── templates/            # HTML templates
    └── index.html       # Main page template
```

## How It Works

The application uses:
- Flask for the web server and routing
- OpenCV for video capture and processing
- Haar Cascade Classifiers for face and eye detection
- Flask's Response class for streaming video
- HTML templates for the web interface

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- OpenCV team for the computer vision library
- Flask team for the web framework
- Haar Cascade Classifiers by OpenCV
