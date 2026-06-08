# URL Shortener Spring Boot

A simple URL Shortener web application built using Java, Spring Boot, Thymeleaf, and Gradle. The application allows users to convert long URLs into short, shareable links and redirect users to the original destination URL.

## Features

* Generate short URLs from long URLs
* Redirect short URLs to the original links
* User-friendly web interface
* Built with Spring Boot and Thymeleaf
* Lightweight and easy to deploy

## Tech Stack

* Java
* Spring Boot
* Spring MVC
* Thymeleaf
* Gradle
* HTML/CSS

## Project Structure

```text
src/
├── main/
│   ├── java/
│   │   └── com/example/URLShortenerService/
│   ├── resources/
│   │   ├── templates/
│   │   └── application.properties
│   └── ...
```

## Getting Started

### Prerequisites

* Java 17 or higher
* Gradle

### Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/url-shortener-springboot.git
```

2. Navigate to the project directory:

```bash
cd url-shortener-springboot
```

3. Run the application:

```bash
./gradlew bootRun
```

For Windows:

```bash
gradlew.bat bootRun
```

4. Open your browser and visit:

```text
http://localhost:8080
```

## Usage

1. Enter a long URL.
2. Click the shorten button.
3. Copy the generated short URL.
4. Use the short URL to redirect to the original website.

## Learning Outcomes

* Spring Boot application development
* MVC architecture implementation
* URL redirection handling
* Template rendering using Thymeleaf
* Gradle project management

## Future Enhancements

* User authentication
* URL analytics and click tracking
* Custom short URLs
* QR code generation
* Database integration

## Author

Priyansh Kushwaha

## License

This project is available for educational and learning purposes.
