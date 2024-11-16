# We are going to use an app called intaSend . go to google and type intaSend sandbox, register to use account . On integation you will see api key. In your button , you should also embed currency converter extra wrapper.

# What does intaSend do?

intaSend takes the complexity of conversions, integrating raw card, google pay, apple pay, M-pessa fro kenyans, Opay for nigerians, together with stripe into your web application to cater for global and local clients.

# go through the intaSend documentation to see how it works focusing on (accepting payment).

1. # install intasend plugin:
   paste it on the head of your html as your script below the css href link.

<script src="https://unpkg.com/intasend-inlinejs-sdk@4.0.5/build/intasend-inline.js"></script>

2. # on the documentation, copy code from there and paste on your html button.

# create the payment button and paste it there.

<button class="intaSendPayButton" data-amount="10" data-currency="KES">Pay Now</button>

3. # On the documentation, you wil see a javascript code there, copy it and paste on your javascript to call your payment button

# Note :

when you want to start receiving real money,you won't use demo api key anyone, you will go to your account and switch to live, then copy the new api key and paste on the html. Also, change that live:false to live:true
