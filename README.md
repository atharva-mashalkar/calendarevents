Get Your Upcoming Goolge Calendar Events

Welcome!!

To run my project you need to go to https://googlecalendarevents.herokuapp.com as I have not uploaded the credentials to get access to Google Calendar api or Google Mail api in this repository.

If you want to see my files you can always clone it.

How it works...

User needs to give his email address where he wants his events to be mailed.
If he is entering the email for the first time then he gets a verification mail on the same email address he entered.(In order to check if the mail he entered is valid as the user might have made a typing error!).If user does not get the verification mail in a minute then please enter the same email again by going back to home page then he will definately get his verification mail as sometimes gmail shows some errors in handling nodemailer requests.Basically I have added this verification feature just to ensure that some unkown person does not spam anyone with some random events using my mail id.
Continuing the process , at this point(verification point) if the user wants to go back and enter a new email he can always click the verified button which will redirect him back to the home page. Even if the user leaves the verification page unhandled for 15 minutes the page redirects itself back to home page where the user can again enter his email.
If you are entering a verified email(email that has gone through a verification process by us!)then you will be redirected to a page where you can choose your account whose calendar events you want to see.The app will ask a few permissions to the user.On approval of these permissions the user will recieve a mail containing his upcoming events.
Note that even if the user is going through email verification process.At the end of verification he is redirected to the same page where he gets to choose his account from which he wants his calendar events.

At the end user should check the attachment in his mail with subject "Google Events" and titled "Your Upcoming Events" .

Thank You.
