# SoftEng Health Club Management System

## Overview

SoftEng Health Club Management System is a software prototype designed to streamline the membership management process for a health or exercise club called SoftEng. This system allows efficient tracking of membership details, member attendance, renewal notifications, and generation of various reports for the club manager.

## Contributors

- Scrib Goode
- Daniel Gaevskiy
- Iman Safari
- Rue Yin Hu
- Ryan Walentowicz
- Zarak Tariq

## Functional Needs Statement

SoftEng Health Club operates with a membership model where users pay an upfront fee for a specified duration, granting them unlimited access during that period. Memberships range from 6 months to 3 years, with varying prorated fees.

Key Features:
- Unique ID number generated upon registration.
- QRCodeID for quick member identification.
- Recording and notification of member visits.
- Membership renewal on the spot.
- Monthly renewal notices.
- Manager reports for inactive members and other analytics.
- Email notifications for membership expiration and promotions.

## Code Outline

### Project Structure

The project contains all functions inside the `com.example` package, containing the following classes:

- **Database:** Manages the storage and retrieval of member information.
- **DataFilters:** Implements filters for member data based on various criteria.
- **FreqSorter:** Sorts members by visit frequency, identifying the most frequent users.
- **Member:** Represents a club member with attributes such as name, age, email, etc.
- **MemberSignUp:** Handles the registration and sign-up process for new members.
- **TestingFile:** Contains code for testing various functionalities.

### Prototype Status

This is a prototype, and will need additional refinements, information, and organization.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/imaboss90/HealthSoftEngClub.git
2. Open the project in your preferred IDE.

3. Customize and extend the code as needed based on project requirements.
## Contributing

Feel free to contribute to the development of this project by forking the repository and submitting pull requests.

### Branching Workflow

To facilitate collaboration, it's recommended to create separate branches when working on new features or making changes. This way, you can update, change, or add things to your branch independently, and the team can review and integrate your changes.

#### Steps to Create a New Branch:

1. **Create a new branch locally:**
   ```bash
   git checkout -b your-branch-name
   ```
   Replace `your-branch-name` with a meaningful name for your branch.

2. **Make and stage your changes:**
   ```bash
   git add .
   ```

3. **Commit your changes:**
   ```bash
   git commit -m "Your commit message here"
   ```

4. **Push your branch to the remote repository:**
   ```bash
   git push origin your-branch-name
   ```
   This makes your branch available to others on the remote repository.

#### Steps to Merge Your Changes (When Ready to Integrate with Main):

When you have completed your work and are ready to integrate it with the main branch, follow these steps:

1. **Switch back to the main branch:**
   ```bash
   git checkout main
   ```

2. **Pull the latest changes from the main branch:**
   ```bash
   git pull origin main
   ```
   This ensures that you have the latest changes from the main branch before merging.

3. **Switch back to your branch:**
   ```bash
   git checkout your-branch-name
   ```
   Now you're back in your branch to integrate your changes with the main branch.

4. **Merge the latest changes from the main branch into your branch:**
   ```bash
   git merge main
   ```
   This step merges the latest changes from the main branch into your branch. Be cautious of potential conflicts.

   **Warning:** In case of conflicts, Git does not automatically override your changes with those from the main branch. Instead, it prompts you to manually resolve conflicts before finalizing the merge.

5. **Resolve any conflicts:**
   If there are conflicts during the merge, Git will prompt you to resolve them manually. Open the conflicted files, make necessary adjustments, and then continue the merge.

6. **Commit your changes:**
   ```bash
   git commit -m "Merge main into your-branch-name"
   ```
   This commits the merged changes to your branch.

7. **Push your changes to the remote repository:**
   ```bash
   git push origin your-branch-name
   ```
   Pushing the changes to the remote repository completes the integration process.

**Warning:** Merging can lead to conflicts if changes in your branch and the main branch overlap. Always review the changes carefully and communicate with your team to minimize conflicts.
```
This branching workflow helps keep the project organized and allows for smoother collaboration. Make sure to communicate with the team about the branches you're working on.
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
