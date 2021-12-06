Requirements
------------

  - [Docker](https://www.docker.com)
    - [Docker Compose](https://docs.docker.com/compose/)
  - [GNU Make](https://www.gnu.org/software/make/) (optional)

Installation
------------
  
  1. Clone the repository

         git clone git@github.com:PHLAK/adguard-home-compose.git

  2. Initialize the configuration files

          make init

      or manually

         cp --verbose .skelleton/config/*.env config/
         cp --verbose .skelleton/.env .

  3. Set the environment variables in `.env`

  4. Set the application-specific environment variables by editing the files found in the `config` directory

  5. Run `docker-compose config` to validate and confirm your configuration

  6. Run `docker-compose up -d` to start the containers
