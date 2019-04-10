# Week 11 - Passwords

In this class we will look at three subjects,
namely Social Engineering, Denial of Service attacks, and handling of passwords and secrets.
The first subject is about to gain information including passwords,
from people using social skills,
as a the way in contrast to traditional hacking,
that uses code.
The second is about how to make a service unavailable,
normally by attacking it with heavy traffic and means to avoid such attacks.
The third is about securing passwords and other sensitive data.

## Social Engineering

* [What is Social Engineering](https://www.csoonline.com/article/2124681/social-engineering/what-is-social-engineering.html)
* [Social Engineering - Wikipedia](https://en.wikipedia.org/wiki/Social_engineering_(security))
* [Video](https://youtu.be/lc7scxvKQOo)

I øvrigt, hvad er forskellen på disse links:
```
https://nordea.dk
https://nοrdeа.dk
```

## Denial of service

* [Denial of Service - Wikipedia](https://en.wikipedia.org/wiki/Denial-of-service_attack)

## Slides

[Slides](https://github.com/SecurityDatFall2018/Week-13/blob/master/Social%20Engineering%20and%20DoS.pptx)

## Exercise

Create a socket based HTTP POST DoS Attack

[Example Code](https://github.com/SecurityDatFall2018/Week-13-Code)

## Handling passwords and secrets

- Watch this [video](https://www.youtube.com/watch?v=O6cmuiTBZVs) to get a bacis idea about handling passwords, and the BCrypt algorithm
- Read this [article](http://dustwell.com/how-to-handle-passwords-bcrypt.html) to get a better understanding
- Skim this [article]() to see that size/complexity of the keys/secrets used to sign cookies, JSON Web Token etc. MATTERS. Read the section "Prevention"
- Read this article [Protecting Secrets in Use](https://www.unboundtech.com/protecting-secrets-in-use-the-long-version/)
- Skim this articles related to handling credit card info [PCI DSS Quick Reference Guide](https://www.pcisecuritystandards.org/documents/PCI%20SSC%20Quick%20Reference%20Guide.pdf)


### Learning Goals

After this week you will:

* Know different ways to use Social Engineering
* Know ways to detect social engineering attemts
* Know the most common DoS strategies
* Know common means to minimize threads of DoS
* Know how to protect passwords preventing the use of rainbow tables.
* Have an idea of regulations for handling credit card data.

### Exercises

* [Password handling](https://docs.google.com/document/d/1eS3u_N6LQtYgBWa21iW9t17lRJElmlVAQA131SoNO78/edit?usp=sharing)
*  Create a socket based HTTP POST DoS Attack. Example code in this repository.

### Exam questions

#### Social Engineering, Denial-of-service attacks
* Explain different ways to use Social Engineering (vectors)
* Discuss ways to detect social engineering attempts (principles)
* Explain the most common DoS strategies
* Discuss common means to minimize threads of DoS

#### Handling Passwords and Secrets

* Explain why it’s always a problem to store user passwords in plain text in our database
* Explain about the different hashing algorithms available, and why slow is good
* Demonstrate, or show a timing diagram, about Bcrypts perfomance (time) for increasing number of rounds
* Demonstrate how BCrypt stores Hash and Salt values and explain the two terms
