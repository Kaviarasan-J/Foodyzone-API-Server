# 🍲 FoodyZone API

FoodyZone is a RESTful API built with **Node.js** and **Express** that serves food data for a culinary application. The API provides information on various dishes, including their names, prices, descriptions, images, and meal types, allowing easy integration into front-end applications.

## 🛠️ Technologies Used
- **Node.js**: Server runtime environment.
- **Express**: Web framework for building RESTful APIs.
- **Path**: For handling and transforming file paths.
- **Cors**: Enables cross-origin requests, allowing the API to interact with a front end.
  
## ✨ Key Features
- **Serves Food Data**: Provides a list of food items, each with name, price, description, image, and type.
- **Static Image Hosting**: Hosts images under the `/images` route to serve food images to the client.
- **CORS Support**: Allows API to be used by various front-end applications.
  
## 📂 Project Structure
- **`index.js`**: The main file that initializes the Express server and serves endpoints.
- **`/public/images`**: Folder containing static images used by the API.

## 🚀 Getting Started
### Prerequisites
- **Node.js** and **npm** installed.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/foodyzone-api.git
   ```
2. Navigate to the project directory:
   ```bash
   cd foodyzone-api
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

### Running the Server
To start the server, run:
```bash
node index.js
```
The server will start at `http://localhost:9000`.

## 🛣️ API Endpoint
- **`GET /`**: Returns a JSON array of food items, each with:
  - `name`: Name of the food item.
  - `price`: Price of the food item.
  - `text`: Description of the food item.
  - `image`: Path to the food item's image.
  - `type`: Type of meal (e.g., breakfast, lunch, dinner).

### Example Response
```json
[
  {
    "name": "Boiled Egg",
    "price": 10,
    "text": "Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, voluptatum.",
    "image": "/images/egg.png",
    "type": "breakfast"
  },
  {
    "name": "Ramen",
    "price": 25,
    "text": "Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam, voluptatum.",
    "image": "/images/ramen.png",
    "type": "lunch"
  }
]
```

## 📝 Future Enhancements
- [ ] Add more endpoints for detailed food descriptions.
- [ ] Integrate a database to store and retrieve dynamic food data.
- [ ] Add search and filter options for meal types.

## 👨‍💻 Author
**Your Name**  
**KAVI J**
