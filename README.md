# stripe-recurring-subscriptions

## Overview

This repository shows you how to create recurring subscriptions with Stripe and Node.js.

It uses Express for creating a simple server, Nunjucks for templating, and the Stripe API.

It features 

1. An **Admin View** when you can create Stripe Products and Plans via the Stripe API.
2. A **Client View** where your users can view and pay for your subscription plans.


## Instructions

1. Clone this repository
2. Run `npm install` to install all dependencies
3. Create a `.env` file to house your Stripe Secret Key (this repo includes `.env` in its `.gitignore`)
4. In the `.env` file, set your secret key as STRIPE_API_KEY (`STRIPE_API_KEY="sk_test_************************"`)
5. In the Javascript section of the `views/signUp.html` file, replace `var stripe = Stripe("pk_test_************************")` with your Stripe Publishable Key
6. Run the app via `npm start`
7. Navigate to [localhost:3000](localhost:3000)
