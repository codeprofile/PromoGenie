# PromoGenie
PromoGenie is an AI-powered application that automates the creation of promotional banners and videos. Designed for businesses looking to streamline their marketing efforts, it takes user inputs such as product images, promotional text, themes, and color palettes to generate high-quality, brand-consistent content quickly.



<img src= "https://github.com/user-attachments/assets/0485d752-c3d0-4257-a01c-b8dde4789d08"  width="50%" height="50%">


## Key Features
- **Dynamic Content Generation**: Automatically create promotional banners and videos tailored to your specifications.
- **User-Friendly Interface**: Intuitive web application built with HTML, CSS, and Bootstrap for easy navigation and input.
- **Image and Video Processing**: Utilizes OpenCV and Moviepy for efficient media processing and generation.
- **AI-Driven Design Suggestions**: Leverages Gemini AI to provide design recommendations based on user inputs.

## Technologies Used
- **Backend**: Python, Flask
- **Image Processing**: PIL, OpenCV
- **Video Generation**: Moviepy
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **AI**: Gemini AI (GenAI)

## Getting Started
To run this project locally, follow these steps:

### Prerequisites
- Python 3.x
- Flask
- Required Python libraries (see `requirements.txt`)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/promoGenie.git
   cd promoGenie
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Flask application:
   ```bash
   python app.py
   ```

4. Open your web browser and go to `http://127.0.0.1:5000` to access the application.

## Usage
- Upload product images and provide promotional details in the input forms.
- Select themes and color palettes to customize your banners/videos.
- Download the generated media for use in your marketing campaigns.

## Challenges I Encountered
During development, I faced challenges such as ensuring high-quality dynamic content generation while maintaining brand consistency. This was addressed by implementing an adaptive design system and performing iterative user testing.

## Future Improvements
- Enhanced AI recommendations for more personalized designs.
- Multi-language support for a broader audience.
- Integration with social media platforms for automated posting.

## Acknowledgments
- [Gemini AI](https://www.example.com) for providing AI capabilities.
- OpenCV and Moviepy for their powerful media processing libraries.
