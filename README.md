# Welcome to the Book Recommendation API

## Overview
Our API allows you to retrieve detailed information about books, including their title, author, publication date, publication name, and even the direct links to download or show images. This API is designed to help developers integrate book search functionality into applications, websites, or services. Whether you're building a book recommendation platform, a digital library, or a book review website, our API provides the data you need to enhance your user experience.

### Key Features
- **Book Title**: Retrieve the title of the book.
- **Book Author**: Access the author’s name (only the first author in case of multiple authors).
- **Year of Publication**: Get the publication year of the book.
- **Publisher**: Find the publisher's name.
- **ISBN Identification**: Books are identified by their unique ISBN.
- **Cover Images**: Access URLs to cover images in small, medium, and large sizes (Image-URL-S, Image-URL-M, Image-URL-L).
- **Content-Based Information**: Data sourced from Amazon Web Services for a reliable experience.

### Notes
- Invalid ISBNs have been removed from the dataset.
- URLs for cover images point to the Amazon website.

---

## How to Access the API

### Prerequisites
- A RapidAPI account
- An API token (available through RapidAPI)

### Steps to Get Started

1. **Sign Up on RapidAPI**
   - Visit [RapidAPI](https://rapidapi.com/robotfa-robotfa-default/api/books-recommendation-270k-books) and create an account if you don’t already have one.

2. **Subscribe to the API**
   - Search for the "Book Recommendation API" and subscribe to it.

3. **Get Your API Token**
   - After subscribing, navigate to the API's "Endpoints" section and copy your unique API token.

4. **Integrate the API**
   - Use the token to authenticate your requests. Here’s an example in cURL:
     ```bash
     curl -X GET "https://books-recommendation-270k-books.p.rapidapi.com.rapidapi.com/list" \
     -H "X-RapidAPI-Key: YOUR_API_KEY" \
     -H "X-RapidAPI-Host: books-recommendation-270k-books.p.rapidapi.com"
     ```

---

## Example Endpoints

### 1. Get Book Details
Retrieve detailed information about a specific book:
```bash
GET /list
```


---

## Contribution
If you have suggestions or would like to contribute to this project, feel free to open an issue or submit a pull request.

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.
