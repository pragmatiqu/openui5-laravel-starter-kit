# OpenUI5 + Laravel Starter Kit 🚀

**Kickstart your SaaS projects with the power of OpenUI5 and Laravel!**  

This repository provides a modular foundation for building enterprise-grade web applications using Laravel as the backend and OpenUI5 for the frontend.

## 🚩 Features

- **Laravel Backend**: Preconfigured for OData services and CRUD operations.
- **OpenUI5 Frontend**: Modular design with reusable components and seamless integration with Laravel.
- **Demo Data**: Example entities for quick experimentation.
- **Fully Documented**: Step-by-step instructions to set up, customize, and extend the kit.

## 📦 What’s Inside?

1. **Backend**

- Laravel 11 setup with API endpoints.
- Example OData v4 services.
- Authentication and basic middleware.

3. **Frontend**

- OpenUI5 project scaffolded with SAP Fiori design principles.
- Example components (e.g., tables, forms, dashboards).
- Integration with backend services.

4. **Utilities**

- Database seeder scripts for demo data.
- Helper classes for OData integration.

## 🛠️ Getting Started

### Prerequisites

- PHP 8.1+ and Composer
- Node.js 16+ and npm
- Docker (optional, for a quick setup)

### Installation

1. **Clone the repository**

```bash
git clone https://github.com/your-username/openui5-laravel-starter-kit.git
cd openui5-laravel-starter-kit
```

2. **Set up the environment**

- Copy `.env.example` to `.env` in the `backend` directory.
- Update the database and app credentials.

3. **Install backend dependencies**

```bash
cd backend
composer install
```

4. **Seed sample data**

```bash
php artisan migrate --seed
```

5. **Install frontend dependencies**

```bash
cd ../frontend
npm install
```

6. **Run the application**

```bash
npm start
```

### Demo

Access the application in your browser at [http://localhost:8080](http://localhost:8080).

## ✨ How to Use

- **Customize Components**: Modify the OpenUI5 views to match your UI needs.
- **Extend Backend Functionality**: Add routes, controllers, or services to build new features.
- **Leverage Demo Code**: Use provided examples as a template for your business logic.

## 🎓 Learn More

- **[Blog Articles](https://pragmatiqu.io)**: Tutorials, tips, and insights on SaaS development with OpenUI5 and Laravel.
- **[Documentation](https://pragmatiqu.io)**: Comprehensive guide to using this starter kit.
- **[Newsletter](https://pragmatiqu.io/openui5-into-the-wild)**: Stay updated with actionable SaaS development insights.

## 🤝 Contributing

Contributions are welcome! If you have ideas or improvements, please submit a pull request.

## 📜 License

This project is licensed under the **Apache License 2.0**. See the [LICENSE](LICENSE) file for details.
