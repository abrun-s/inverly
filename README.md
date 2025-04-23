# Inverly

Inverly is a **stock market ETF comparison** web application that lets users track, compare, and visualize the performance of multiple Exchange–Traded Funds over time. :contentReference[oaicite:0]{index=0}

## Features

- **User authentication & management** via Devise (sign up, log in/out).  
- **ETF catalog**: search for ETFs by ticker, view details, and add to your personal list.
- **Favorites**: mark your most-watched ETFs for quick access.  
- **Investment tracking**: record contributions and holdings per ETF, with automatic grouping by month. 
- **Interactive charts** powered by Chartkick & Groupdate for historical performance and contribution trends.  
- **Responsive UI** styled with Bootstrap 5 and Font Awesome for seamless desktop & mobile experience.

## Tech Stack

- **Ruby 3.3.5** & **Rails ~> 7.1.5**   
- **PostgreSQL** as the database  
- **Hotwire** (Turbo & Stimulus) for fast, SPA-like navigation   
- **Puma** web server  
- **Devise** for authentication, **Simple Form** for forms   
- **Chartkick**, **Groupdate** & **Faker** for charting and seeding demo data   
- **Docker** support via provided Dockerfile

## Installation

1. **Clone the repo**  
   ```bash
   git clone https://github.com/abrun-s/inverly.git
   cd inverly

2. Install dependencies
    ```bash
   bundle install

4. Set up environment variables
    ```bash
    Copy .env.example to .env and fill in your database credentials and any API keys you plan to use.

5. Initialize the database
    ```bash
    rails db:create db:migrate db:seed

6. Start the server
    ```bash
    rails server

Open http://localhost:3000 in your browser and sign up for a new account.

**Contributing**
1. Fork the repository
2. Create your feature branch (git checkout -b feature/YourFeature)
3. Commit your changes (git commit -m "Add awesome feature")
4. Push to the branch (git push origin feature/YourFeature)
5. Open a Pull Request
