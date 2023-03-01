Sgoettschkes/dbt-fundamentals
-----------------------------

## Installation

    asdf install
    poetry install

Copy the content from `profiles.example.yml` into your local `.dbt/profile.yml`. Make sure the database credentials are correct.

Run `poetry run dbt debug --project-dir dbt_fundamentals/` and make sure dbt can run and connect to your database.

## Database setup

Connect to your database and execute `data/schema.sql` to create the schemas and tables needed for the fundamentals course. Import the `jaffle_shop_customers.csv` into the table `jaffle_shop.customers` and the file `jaffle_shop_orders.csv` into the table `jaffle_shop.orders`. The file `stripe_payments.csv` should be imported into `stripe.payment`.
