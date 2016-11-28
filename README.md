# EmployMe Chatbot

Chatbot for Civic Tech Toronto's 2016 [Youth Employment Challenge](http://civictech.ca/2016/10/12/announcing-youth-employment-civic-tech-challenge/)

EmployMe is a chatbot that helps direct relevant resources to job seekers, particularly unemployed youth ages 18-29. Built on top of the Facebook Messenger Bot platform, EmployeMe has several functionalities, including: directing job seekers to job postings, meet ups and networking events by relevant keywords; educating users to their legal rights and provincial labor law (particularly to do with unpaid internships); enabling job seekers to search company reviews on Glassdoor, and more.

We're still in Beta, but we have a [Facebook Page!](https://www.facebook.com/employmechatbot/)

## Tech Stack

Our bot was built using Node.js and the Facebook Graph API, prototyped in Sketch, and deployed on Heroku.

![Employ Me - Demonstration](http://i.makeagif.com/media/11-28-2016/Mp9LDd.gif)

See a larger demo [here](https://youtu.be/ruEWwD40Pi8).

## Links

- Michelle Lee [GitHub](http://github.com/mi-lee)
- Sonal Ranjit [GitHub](https://github.com/sonalranjit)
- [Civic Tech Toronto](http://civictech.ca/)
- [2016 Youth Employment Challenge](http://civictech.ca/2016/10/12/announcing-youth-employment-civic-tech-challenge/)

## Contributing

To try out our baby bot on localhost, simply clone the repo and

```
npm install
npm start
```

and navigate to localhost. For debugging, we used [ngrok](https://ngrok.com/) and replaced the callback URL on Facebook Developers site with the temporary ngrok url.

## Other future ideas include:

- OCR from photos of business cards to be emailed directly
- One-click job applying using LinkedIn API
- Reminders from EmployMe
