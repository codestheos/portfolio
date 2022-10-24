## To make the contact form work

- Create a account in [emailjs](https://www.emailjs.com/) create also new Outlook or Gmail account to be able
  to send email.
- Create a new service, select and log in to your newly created outlook or gmail account on EmailJS.
- Go back to the dashboard and get the Service ID copy it.
- Create a .env file in your root folder and put

```

NEXT_PUBLIC_USER_ID = 'YOUR_USER_ID'
NEXT_PUBLIC_TEMPLATE_ID = 'template_fqqqb9g'
NEXT_PUBLIC_SERVICE_ID = 'YOUR_SERVICE_ID'

```

into it. Replace \*your user id and your service ID with your values in your EmailJS service.