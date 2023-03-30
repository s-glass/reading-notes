# 301 class 14 notes

**Why this matters**: This information matters because understanding and increasing diversity and inclusion in the workplace is necessary to increase innovation, product quality, and social equity.

------------------------------------

## That Time When Women Stopped Coding

Source: [https://www.npr.org/sections/money/2014/10/21/357629765/when-women-stopped-coding](https://www.npr.org/sections/money/2014/10/21/357629765/when-women-stopped-coding)

**1. What occurred during the same time as the beginning of the decline of women in computer science?**

Personal computers started showing up in U.S. homes in significant numbers, and marketing targeted computers almost exclusively to men and boys.

**Why does it matter that males had been playing on computers growing up?**

Because it started to become assumed that computers were made for men and boys. As such, these assumptions were excluding women in school and at work. For example, starting in the 80's, computer science professors started assuming that their students had grown up playing with computers at home - and curriculum therefore catered to students who had that exposure and experience.

----------------------------

## Why diversity matters to your tech industry

Source: [https://www.usatoday.com/story/tech/columnist/2015/07/21/why-diversity-matters-your-tech-company/30419871/](https://www.usatoday.com/story/tech/columnist/2015/07/21/why-diversity-matters-your-tech-company/30419871/)

**1. When are diversity efforts most successful?**

When they're driven by a commitment from company leaders.

**2. Why do diverse companies perform better?**

Because diverse groups of people bring more and different ways of seeing a problem and thus, faster and better ways of solving it. They are smarter and more creative than homogenous ones.

**3. Give an example of how a diverse company can serve a diverse user base or vise-versa.**

The more diverse a company is, the more they could be able to create products and features that consider multiple wants and needs, in addition to having different insights on how to increase engagement and build networks and partnerships in various communities.

An example is that if YouTube had considered the experiences of left handed people when building their iOS app, they could have avoided significant user errors.


------------------------------------
### Things I Want To Know More About:
Nothing at the moment!








# 301 class 15 notes

**Why this matters**: This information matters because it provides basic information about authorization, why it's important, and what its vulnerabilities are.

------------------------------------

## What is OAuth

Source: [https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)

**1. What is OAuth?**

An open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential.

**2. Give an example of what using OAuth would look like.**

When a user logs onto a website, it offers one or more opportunities to log on using another website or service's logon. When the user clicks a button linked to another site, the other site authenticates the user and the site originally sought after logs the user on itself using permission gained from the second website.

**3. How does OAuth work? What are the steps that it takes to authenticate the user?**

After a user signs into one website or service (using HTTPS), the user then initiates a feature or transaction that needs to access a different site or service. At that point, these 11 steps are followed: 

1. The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.
2. The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.
3. The first site gives this token and secret to the initiating user’s client software.
4. The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).
5. If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.
6. The user approves (or their software silently approves) a particular transaction type at the first website.
7. The user is given an approved access token (notice it’s no longer a request token).
8. The user gives the approved access token to the first website.
9. The first website gives the access token to the second website as proof of authentication on behalf of the user.
10. The second website lets the first website access their site on behalf of the user.
11. The user sees a successfully completed transaction occurring.


**4. What is OpenID?**

Where OAuth is about authorization, OpenID is about authentication. "OpenID is for humans logging into machines, OAuth is for machines logging into machines on behalf of humans."

----------------------------

## Authorization and Authentication flows

Source: [https://auth0.com/docs/get-started/authentication-and-authorization-flow](https://auth0.com/docs/get-started/authentication-and-authorization-flow)

**1. What is the difference between authorization and authentication?**

Authentication is the process of verifying who a user is, and authorization is the process of verifying what they have access to.

**2. What is Authorization Code Flow?**

Authorization Code Flow exchanges an Authorization Code for a token used in server-side apps.

**3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?** 

During authentication, apps can use ACF as long as there's additional security via a Proof Key for Code Exchange.

**4. What is Implicit Flow with Form Post?**

For apps that are unable to safely secure Client Secrets, Implicit Flow, when used with Form Post response mode, offers a streamlined workflow if the app needs only an ID token to perform user authenticaiton.

**5. What is Client Credentials Flow?**

With machine-to-machine apps, where the system authenticates and authorizes an app as opposed to a user, M2M apps need to use the Client Credentials Flow. In CCF, the app passes their Client ID and Client Secret to authenticate themselves and receive a token.

**6. What is Device Authorization Flow?**

For input-constrained devices connecting to the internet, the device asks the user to go to a link on their computer or smartphone to authorize the device. This assists devices without an easy way to enter text.

**7. What is Resource Owner Password Flow?**

It requests that users provide credentials like username and password, typically through an interactive form, to highly-trusted applications.

------------------------------------
### Things I Want To Know More About:
Nothing at the moment!