
## Project Overview: 
The platform addresses the challenge of unreliable power supply in Africa, specifically in Nigeria, by providing a system for renting and sharing batteries and energy sources. The concept revolves around using solar-powered battery hubs where people can rent fully charged batteries to power their homes, appliances, or devices. This system operates similarly to Uber's bike and scooter rentals but focuses on essential energy needs.

### Target Features
**Frontend:**
To List features as part of Readme
- Feature 1
- Feature 2

**Backend:**
To List features as part of Readme
- Feature 1
- Feature 2

**Cloud Engineering:** 
To List features as part of Readme
- Feature 1
- Feature 2


## Contribution guidelines

Thank you for considering contributing to this project! Please adhere to the following guidelines:

- **Branch Naming:** Use the format `feature/description` for new features and `bugfix/description` for bug fixes.
- **Commits:** Write clear, concise commit messages.
- **Pull Requests:** Ensure your PRs are well-documented and linked to relevant issues.

For detailed guidelines, refer to [GitHub's contributing guidelines](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors).

### Getting started

1. **Ensure Git is installed on your local**

2. **Clone the repo**

```bash
git clone git@github.com:Althub-Team17/Project.git
```
3.  **Navigate to the Cloned Repository:**
```bash
cd project
``` 
4. **Navigate to required folder within the cloned repository (Eg frontend) to add your feature.**
```bash
cd frontend
```

5. **Create a new feature branch**
```bash
git checkout -b feature/updatefeature
```
6. **Make changes and commit (eg)**
```bash 
git add .
git commit -m "feature: Update feature documentation"
```
7. **Push the feature branch**
```bash
git push origin feature/updatefeature
```
8. **Create a Pull Request, get approval, and merge (PR)**
- Navigate to the repository on GitHub.
- Select the feature/updatefeature branch and create a PR against the dev branch.
- Provide a descriptive title and detailed description of your changes.
- The repository maintainers may review your pull request and provide feedback. You can assign a reviewer

9. Review and Merge:
- Collaborators will review the PR and provide feedback if needed.
- Once approved, you or the maintainers will merge your changes into the dev branch of the original repository.

10. Clean up (Optional): 
- After merging, delete your feature branch locally and remotely
Locally
```
git branch -d feature/update-readme
```
Remotely
```
git push origin --delete feature/updatefeature
```

***Additional work flows on admin level***

1. **Testing and Review:**
- CI/CD pipelines should run tests automatically for all branches.
- Perform manual testing on the dev branch once the CI passes.

2. **Merge to Main (Production):**
- Once all tests pass and changes are validated in dev, open a PR to merge dev into main.
- Repeat code review and testing for main before deployment
