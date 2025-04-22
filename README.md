# Social Media Post Generator

A modern, minimalist web application that generates engaging social media posts using AI. Built with Flask and styled with a sleek dark theme.

![Post Generator Interface](screenshot.png)

## Features

- 🎨 Modern, dark-themed UI with minimalist design
- 📱 Support for multiple social media platforms:
  - Facebook
  - Instagram
  - LinkedIn
- ⚡ Real-time post generation
- 📋 One-click copy to clipboard
- 🔄 Loading indicators for better UX
- 📱 Responsive design
- 🎯 Platform-specific post optimization

## Tech Stack

- **Backend**: Python Flask
- **Frontend**: HTML5, CSS3, JavaScript
- **Font**: Inter (Google Fonts)
- **Icons**: Font Awesome 6
- **API Integration**: Webhook-based content generation

## Setup

1. Clone the repository:
```bash
git clone <repository-url>
cd social-media-post-generator
```

2. Create a virtual environment and activate it:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run the application:
```bash
python app.py
```

5. Open your browser and navigate to:
```
http://localhost:5000
```

## Usage

1. Select your target social media platform from the dropdown
2. Enter a trending topic or subject
3. Click "Generate Post"
4. Wait for the AI to generate your post
5. Use the "Copy to Clipboard" button to copy the generated content
6. Paste and publish on your chosen platform

## Configuration

The application uses a webhook URL for post generation. To configure your own webhook:

1. Open `templates/index.html`
2. Locate the webhook URL in the JavaScript section
3. Replace with your own webhook URL

## Development

To modify the styling:
- Edit `static/css/style.css` for visual changes
- Update `templates/index.html` for structural changes

## Deployment

The application can be deployed to various platforms:

### Render
1. Create a new Web Service
2. Connect your repository
3. Set build command: `pip install -r requirements.txt`
4. Set start command: `gunicorn app:app`

### Other Platforms
- Heroku
- PythonAnywhere
- AWS Elastic Beanstalk

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Font Awesome for icons
- Google Fonts for the Inter font family
- Flask community for the excellent web framework 