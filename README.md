# Practice AI - Customer Management API

A practice project for AI development featuring a robust Node.js REST API for customer management with FieldRoutes integration and field routing services.

## 🚀 Features

- **Customer Management**: Complete CRUD operations for customer data
- **FieldRoutes Integration**: Seamless integration with FieldRoutes API
- **Field Routing Services**: Advanced routing capabilities for field operations
- **Comprehensive Testing**: Full test suite with Jest and Supertest
- **Security**: Built-in security middleware with Helmet and CORS
- **Rate Limiting**: Configurable rate limiting to prevent abuse
- **Error Handling**: Centralized error handling with detailed logging
- **Input Validation**: Robust input validation using Joi
- **Logging**: Structured logging with Winston

## 🛠️ Tech Stack

- **Runtime**: Node.js
- **Framework**: Express.js
- **Testing**: Jest, Supertest
- **Validation**: Joi
- **Logging**: Winston
- **Security**: Helmet, CORS
- **HTTP Client**: Axios
- **Development**: Nodemon

## 📁 Project Structure

```
├── controllers/          # Request handlers and business logic
│   └── customerController.js
├── routes/              # API route definitions
│   └── customers.js
├── services/            # Business services and external API integration
│   └── fieldRoutesService.js
├── middleware/          # Custom middleware
│   ├── errorHandler.js
│   └── validation.js
├── utils/               # Utility functions
│   └── logger.js
├── tests/               # Test suites
│   ├── customers.test.js
│   ├── fieldroutes-integration.test.js
│   └── setup.js
├── examples/            # Usage examples
│   └── usage-example.js
├── logs/                # Log files
├── server.js            # Application entry point
└── API_DOCUMENTATION.md # Complete API documentation

```

## 🔧 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/jonathandavidlewis/practice-ai.git
   cd practice-ai
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Environment Setup**
   Create a `.env` file in the root directory:
   ```env
   NODE_ENV=development
   PORT=3000
   FIELDROUTES_API_URL=your_fieldroutes_api_url
   FIELDROUTES_API_KEY=your_api_key
   FIELDROUTES_USERNAME=your_username
   FIELDROUTES_PASSWORD=your_password
   ```

## 🚀 Usage

### Development Mode
```bash
npm run dev
```

### Production Mode
```bash
npm start
```

### Running Tests
```bash
npm test
```

## 📚 API Documentation

The API provides comprehensive customer management capabilities:

- **GET** `/api/health` - Health check endpoint
- **POST** `/api/customers` - Create a new customer
- **GET** `/api/customers/:id` - Retrieve customer by ID
- **PUT** `/api/customers/:id` - Update customer information
- **DELETE** `/api/customers/:id` - Delete a customer

For detailed API documentation, see [API_DOCUMENTATION.md](./API_DOCUMENTATION.md)

## 🧪 Testing

The project includes comprehensive testing:

- **Unit Tests**: Individual component testing
- **Integration Tests**: FieldRoutes API integration testing
- **API Tests**: Complete API endpoint testing

Run tests with:
```bash
npm test
```

## 🔒 Security Features

- **Helmet**: Security headers middleware
- **CORS**: Cross-origin resource sharing configuration
- **Rate Limiting**: Configurable request rate limiting
- **Input Validation**: Joi-based request validation
- **Error Handling**: Secure error responses

## 📊 Logging

Structured logging with Winston provides:
- Different log levels (error, warn, info, debug)
- File-based logging
- Console output for development
- Request/response logging

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🎯 Learning Objectives

This practice project demonstrates:
- Modern Node.js API development
- RESTful API design principles
- Integration with external APIs
- Comprehensive testing strategies
- Security best practices
- Error handling and logging
- Code organization and structure

## 📞 Support

If you have any questions or need help with setup, please open an issue in the GitHub repository.