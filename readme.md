# Bank Account

This is an application for the purpose of simulating a bank account.

It is possible to carry out incoming and outgoing transactions and check the balance.

How to use?

Install the dependencies
```$ yarn install```

Run the project (port 3333)
```$ yarn dev: server```

Use Postman, Insomnia or whatever you prefer to access the routes of the application.

```GET / transactions``` *Returns your balance and all inflows and outflows*
```POST / transactions``` *Create a new record*

JSON object to create:

{
   title: 'Salary',
   type: 'income',
   value: 3000,
}

Note: the type must be only "income" or "outcome".
