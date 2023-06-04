
# Angular Razorpay Payment Gateway Integration

A simple ecommerce shop web application with real payment gateway integrated in it.

## Environment Variables

To run this project, you will need to add the following environment variables to your keys.json file in backend

`key_id`

`key_secret`

and just `key_id` in frontend's keys.json

WARNING- do not expose `key_secret` in frontend project. 
## Run Locally

Clone the project

```bash
  git clone https://github.com/dnyaneshwargiri/razorpay-payment-gateway-angular
```

Go to frontend the project directory

```bash
  cd angular-payment-gateway
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  ng serve
```
Go to backend the project directory

```bash
  cd backend-service
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm start
```

## Running Tests

To run tests, run the following command

```bash
  npm run test
```


## Demo

[Live Demo](https://razorpay-payment-gateway-angular.vercel.app/)


## Tech Stack

**Client:** Angular 16, Ionic

**Server:** Node, Express


## Lessons Learned

To handle real time payments in angular application.

Create a secure payment workflow using node js and angular.

