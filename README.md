
## Project Overview: 
The platform addresses the challenge of unreliable power supply in Africa, specifically in Nigeria, by providing a system for renting and sharing batteries and energy sources. The concept revolves around using solar-powered battery hubs where people can rent fully charged batteries to power their homes, appliances, or devices. This system operates similarly to Uber's bike and scooter rentals but focuses on essential energy needs.

### Target Features
**Frontend: To List features as part of Readme**
- Feature 1
- Feature 2
**Backend: To List features as part of Readme**
- Feature 1
- Feature 2
**Cloud Engineering: To List features as part of Readme**
- Feature 1
- Feature 2


## Contribution guidelines
### Getting started
How to clone and setup project locally
1. Ensure Git is installed on your local
2. Clone the repo using ssh

```bash
git clone git@github.com:Althub-Team17/Project.git
cd <repository-name>
```
3. Navigate to required folder (Eg Frontend)
```bash
cd frontend
``` 
4. Start inputing code - Start with updating a readme, or creating your folder

5. Create a new feature branch
```bash
git checkout -b feature/<feature-name>
```
6. Make changes and commit (eg)
```bash 
git add .
git commit -m "feature: Insert feature note"
```
7. Push the feature branch
```bash
git push origin feature/<feature-name>
```
8. Pull Requests
- Open a PR to merge feature/* into dev.
- Assign team members for a code review.
- Once approved, merge the branch into dev.

9. Testing and Review:
- CI/CD pipelines should run tests automatically for all branches.
- Perform manual testing on the dev branch once the CI passes.

10. Merge to Main (Production):
- Once all tests pass and changes are validated in dev, open a PR to merge dev into main.
- Repeat code review and testing for main before deployment
