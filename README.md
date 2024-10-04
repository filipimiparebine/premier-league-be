# Premier League Simulation

This project is a Premier League football simulation application built with Laravel 10 (backend) and Next.js (frontend).

## Features

- Team selection
- League table generation
- Week fixtures (week matches to be played)
- Match simulation
- Match prediction
- Unit and feature testing with PHPUnit
- Dockerized
- Github CI Pipelines

## Setup

1. Clone the repository:

```bash
git clone https://github.com/filipimiparebine/premier-league-be.git
cd premier-league-be
```

2. Create a `.env` file in the backend directory and configure your database settings.

3. Build and run the Docker containers:

```bash
docker-compose up -d --build
```

5. Access the application at `http://localhost:3000`

## Running Tests

To run the backend tests:

```bash
docker-compose exec backend vendor/bin/phpunit
```

## CI/CD

This project uses GitHub Actions for continuous integration. The workflow is defined in `.github/workflows/ci.yml`.

## License

This project is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
