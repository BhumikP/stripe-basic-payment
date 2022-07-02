Steps to Build run the app with

1>Create stripe account from `https://stripe.com/in` .

2> Search for developers API Keys and and add Publishable key in stripe-payment/src/Stripe/StripeContainer PUBLIC_KEY.

3>Create an .env file in  stripe-server , then add secret key from stripe dashboard to .env file as **STRIPE_SECRET="YOUR_STRIPE_SECRET_KET"** Also add PORT if you want to.

4> Go to stripe-payment and run `npm i` then `npm start`

5> Go to stripe-server and run `npm i` then `npm start`

6> You will see your app is running on `localhost:3000`

7> Add VISA details and do payment , Check console to see Successfull payment.

8> Also you can see the payments done in Stripe's Dashboard.