Project Description:

This project is focused on creating a product management system with an emphasis on simplifying product data entry and enhancing it using AI services. The system allows users to register products by either uploading a CSV file with product details or by submitting 4 product photos along with a brief description.

Once the product data is received, it is processed through an Azure OCR service that extracts product characteristics from the images. Using AI, the system generates a detailed product description, title, and tags based on the OCR data and photos.

The products are then stored in a PostgreSQL database with the flexibility to enhance product data over time. The system also integrates with an AI-driven search engine to make the products searchable and accessible to users.

The application will include user authentication via JWT and will be built using NestJS for the backend, ensuring scalability and security. The platform will allow users to manage product details, track workflows, and enhance their product listings with ease.

