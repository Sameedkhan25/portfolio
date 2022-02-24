# Personal portfolio

<!-- [![Site preview](/public/social-image.png)](https://hamishw.com) -->

<!-- A design portfolio to showcase a few projects. View the [live site](https://hamishw.com) or check out a live version of the [components storybook](https://storybook.hamishw.com). -->

## Install & run

Make sure you have nodejs and npm installed. Install dependencies with:

```bash
npm install
```

Once it's done start up a local server with:

```bash
npm start
```

To view the components storybook:

```bash
npm run storybook
```

To create a production build:

```bash
npm run build
```

## Deployment

I've set up the site using AWS for hosting and serverless functions. You'll need an AWS account and the AWS CLI installed in order to deploy.

Deploy the site to s3:

```bash
npm run deploy
```

Deploy serverless functions:

```bash
cd functions
```

```bash
npm run deploy:api
```


## Credits
i have forked this site from hamishw, the guy has done a brilliant job. Do checkout his site hamishw.com.


