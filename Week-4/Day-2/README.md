# 📘 DAY 2

## CI/CD Pipeline

Today, we learned about Continuous Integration (CI) and Continuous Delivery/Deployment (CD). These practices help teams automate 
software validation and delivery.

## CI vs CD

- **Continuous Integration (CI):** Developers frequently integrate code changes, which can trigger automated builds and tests.
- **Continuous Delivery:** Keeps changes validated and ready for release, with production deployment potentially requiring approval.
- **Continuous Deployment:** Automatically releases qualifying changes to production after the required checks pass.

## Typical Pipeline Stages

1. **Code:** Developers make and commit changes.
2. **Build:** The application is compiled or packaged when required.
3. **Test:** Automated checks validate the changes.
4. **Release:** A validated version is prepared for delivery.
5. **Deploy:** The version is deployed to the target environment.
6. **Monitor:** The application is observed for errors and performance issues.

## Development, Staging and Production

- **Development:** Used to develop and modify software.
- **Staging:** Used to validate a release before production.
- **Production:** The live environment serving the intended users.

## Deployment Strategies

- **Blue-Green:** Uses two environments and switches traffic from the old version to the new one.
- **Canary:** Releases a new version to a small portion of traffic before expanding the rollout.
- **Rolling:** Updates application instances gradually.

## Key Learnings

- Understood CI, Continuous Delivery, and Continuous Deployment.
- Learned the stages of a typical CI/CD pipeline.
- Differentiated development, staging, and production environments.
- Explored common deployment strategies.

## Conclusion

This session explained how CI/CD pipelines automate software validation and delivery while helping teams manage deployment risks.
