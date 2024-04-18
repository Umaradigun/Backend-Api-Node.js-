Install Dependencies
    For Backend - npm i

Env Variables
Make Sure to Create a config.env file in backend/config directory and add appropriate variables in order to use the app.

Essential Variables PORT= DB_URI = STRIPE_API_KEY= STRIPE_SECRET_KEY= JWT_SECRET= JWT_EXPIRE= COOKIE_EXPIRE= SMPT_SERVICE = SMPT_MAIL= SMPT_PASSWORD= SMPT_HOST= SMPT_PORT= CLOUDINARY_NAME CLOUDINARY_API_KEY CLOUDINARY_API_SECRET fill each filed with your info respectively

ORDER ROUTES
/order/new
/order/:id
/orders/me
    ADMIN
/admin/orders
/admin/order/:id

PAYMENT ROUTE
/payment/process
stripeapikey
