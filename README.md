# Ignite Call

<img src="https://kawan-demo-s3.s3.eu-west-1.amazonaws.com/ignite-call/1.jpg" alt="Ignite Call">

> Ignite Call is a website that integrates with Google Calendar and makes it easy to create appointments for different types of services. The project was deployed by Vercel and the database by Planetscale. In the construction was used:

- Next.js framework.
- React libraries like React Hook Form, React Query.
- Next Libraries like NextAuth, NextSEO.
- DayJs for data processing.
- Nookies for handling cookies in the browser
- Zod for form validation.
- Prisma for database manipulation.

Project link: https://ignite-call-kawan.vercel.app/

## ☕ Using <Ignite Call>

To use <Ignite Call>, fallow these steps:

```
1. Enter the link https://ignite-call-kawan.vercel.app/
```
<img src="https://kawan-demo-s3.s3.eu-west-1.amazonaws.com/ignite-call/1.jpg" alt="step-1">

```
2. Check your username and put your full name information.
```
<img src="https://kawan-demo-s3.s3.eu-west-1.amazonaws.com/ignite-call/2.JPG" alt="step-2">

```
3. Connect your Google Account and allow the permissions to use Calendar API and to get your Google Account Informations.
```
<img src="https://kawan-demo-s3.s3.eu-west-1.amazonaws.com/ignite-call/3.JPG" alt="step-3">

```
4. Select your schedule checking your available days and times.
```
<img src="https://kawan-demo-s3.s3.eu-west-1.amazonaws.com/ignite-call/4.JPG" alt="step-4">

```
5. Put a small description of yourself.
```
<img src="https://kawan-demo-s3.s3.eu-west-1.amazonaws.com/ignite-call/5.JPG" alt="step-5">

```
6. Send your Schedule Link for your users to allow that they schedule a meeting with you. The link probably is:
https://ignite-call-kawan.vercel.app/schedule/yourusername. After this, users can click on available date and time to schedule a meeting with you.
```
<img src="https://kawan-demo-s3.s3.eu-west-1.amazonaws.com/ignite-call/6.JPG" alt="step-6">

```
7. Users need to put their name, email and observations to schedule a meeting with you. After pressing in 'Confirmar' the schedule has been done and you can check in your google calendar.
```
<img src="https://kawan-demo-s3.s3.eu-west-1.amazonaws.com/ignite-call/7.JPG" alt="step-7">

```
8. Check your Google Calendar and enter in a meet link in the scheduled time.
```
<img src="https://kawan-demo-s3.s3.eu-west-1.amazonaws.com/ignite-call/8.JPG" alt="step-8">

## 🚀 Installing <Ignite Call>

If you want to make changes in the project, install and fallow these steps:

Windows/Linux/macOS:

```
1. npm i
2. create a .env and put your credentials of google oauth api.
DATABASE_URL=yourdatabaseurl
GOOGLE_CLIENT_ID=createinoauthgoogleconsole
GOOGLE_CLIENT_SECRET=createinoauthgoogleconsole
NEXTAUTH_SECRET=createanextauthsecretlikeanyhashgenerator
3. npm run dev
4. run npx prisma studio to check the database.
```

To contribute with <Ignite Call>, fallow these steps:

1. Fork this repository.
2. Create a branch: `git checkout -b <branch_name>`.
3. Make your changes and commit them: `git commit -m '<message_commit>'`
4. Push to the original branch: `git push origin <project_name> / <local>`
5. Create the pull request.

Alternatively, see Github documentation in [how to create a Pull Request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

<table>
  <tr>
    <td align="center">
      <a href="#">
        <img src="https://github.com/kawanstrelow.png" width="100px;" alt="Foto do Kawan Strelow no GitHub"/><br>
        <sub>
          <b>Kawan R. Strelow</b>
        </sub>
      </a>
    </td>
    
  </tr>
</table>

[⬆ Back to the top]<br>
