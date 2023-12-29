# RustDesk RDP Setup with GitHub Actions

This repository provides a simple setup for Remote Desktop (RDP) using RustDesk and GitHub Actions. Users can fork this repository and run the GitHub Actions workflow to set up RDP on their remote machine.

## Prerequisites

- [RustDesk](https://rustdesk.com/) installed on your local machine.

## Getting Started

1. **Fork this Repository:**

   Click on the "Fork" button in the top right corner to create a copy of this repository in your GitHub account.

2. **Run GitHub Actions Workflow:**

   - Navigate to the "Actions" tab in your forked repository.
   - Click on the "RDP Setup" workflow.
   - Click on the "Run workflow" button.
   - Confirm by clicking "Run workflow" in the pop-up dialog.

3. **Retrieve RDP Connection Details:**

   - Once the workflow completes, go to the "Actions" tab and find the latest workflow run.
   - Click on the "RDP Setup" job to see the details.
   - Look for the "Log In To RustDesk" section and copy the `RustDesk ID` & `Password`.

4. **Connect with RustDesk:**

   - Open RustDesk on your local machine.
   - Use the RDP connection details copied before.

## Security Considerations

- **Keep Credentials Secure:**
  Be cautious with the RDP credentials. Ensure that only authorized users have access to the details.

## Notes

- This setup assumes a basic configuration. You may need to modify the workflow or add additional steps based on your specific requirements.

- For any issues or improvements, feel free to open an [issue](https://github.com/sh-y-zu/RustDesk-RDP/issues) or submit a [pull request](https://github.com/sh-y-zu/RustDesk-RDP/pulls).

Happy remote desktopping!
