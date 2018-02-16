# page-views

Implement a NodeJS application, which shows the number of pageviews for the past 1 minute.
- Implement transpiling of ES6 code to run on any Node version, starting from 6. Important: keep you build as tiny as possible for each version, depending on which ES6 features are supported by current Node version.
- Implement dockerization of the application. Keep image size as small as possible so that final image doesn’t contain any dev dependencies or not transpiled sources (tip: https://docs.docker.com/engine/userguide/eng-image/multistage-build/#use-multi-stage-builds)
- Build and run locally.

Make your application production-ready.

- Deploy your docker image to AWS, Google Cloud or MS Azure as a load-balanced, horizontally scalable micro-service.
- Implement CI pipeline, which automatically redeploys test application after git push to the master branch.
- Prepare instructions in README.md file about how to deploy your app to production environment for other developers to reproduce.
