<div align="center">
  <h1>Auto-Committer 🤖</h1>
  <!-- <img src="https://raw.githubusercontent.com/themuuln/auto-committer/main/assets/logo.png" alt="Auto-Committer Logo" width="200"> -->
  <p>Automate your GitHub commits and keep your repository history active!</p>
  <p>
    <a href="https://github.com/themuuln/auto-committer/actions">View Actions</a> ·
    <a href="https://github.com/themuuln/auto-committer/issues">Report Bug</a> ·
    <a href="https://github.com/themuuln/auto-committer/pulls">Contribute</a>
  </p>
  <p>
    <a href="https://github.com/themuuln/auto-committer/actions/workflows/auto_commit.yml">
      <img src="https://github.com/themuuln/auto-committer/actions/workflows/auto_commit.yml/badge.svg" alt="Auto Commit">
    </a>
  </p>
</div>

## How it Works

Auto-Committer is a GitHub Action that automates 2 daily commits to your repository. Every hours, it creates a series of empty commits to keep your commit history fresh and active. While the commits are empty and playful in nature, they serve as a motivational reminder to stay committed to your coding endeavors.

## Getting Started

To experience the magic of daily automation, follow these simple steps:

1. **Fork the Repository**:
   Go to the original "Auto-Committer" repository on GitHub (https://github.com/themuuln/auto-committer). Click on the "Fork" button in the top right corner of the repository page. This will create a copy of the repository in your GitHub account.

2. **Change Action Permissions**
   To allow the automated workflow to make commits on your behalf, you need to modify the permissions settings. Here's how:

   In your forked repository, navigate to the "Settings" tab.
   Look for the "Actions" section in the left sidebar and click on it.
   Under the "Workflow permissions" heading, ensure that the permissions are set to "Read and write" for workflows.


3. **Configure the Schedule (Optional)** :
   In your forked repository, navigate to the `.github/workflows/auto_commit.yml` file. This is the workflow file responsible for automating the commits. By default, the workflow runs every three hours. You can customize the schedule by modifying the cron syntax in the file.

   The cron syntax looks like this:
   ```
   * */3 * * *
   | | | | |
   | | | | +----- Day of the week (0 - 7) (Sunday is both 0 and 7)
   | | | +------- Month (1 - 12)
   | | +--------- Day of the month (1 - 31)
   | +----------- Hour (0 - 23)
   +------------- Minute (0 - 59)
   ```
   Update the cron schedule to your preferred timing, if necessary.

4. **Make it Yours**:
   Customize the automation to fit your requirements. The current workflow creates empty commits every three hours. You can modify the workflow to include additional tasks or actions relevant to your personal project needs.

5. **Use GitHub Secrets (Optional)**:
   To enhance security, consider using GitHub Secrets to store sensitive information like Git credentials (username and email) and the Personal Access Token (PAT). Using GitHub Secrets ensures that this sensitive data is not exposed in your workflow files.

6. **Limit Commits (Optional)**:
   The original repository implemented a commit limit to specific intervals (06:00 AM - 06:00 PM UTC) to avoid excessive commits. You can consider keeping this limitation to prevent too many automated commits.

7. **Commit Timestamp (Optional)**:
   To track commit times easily, the original repository added a timestamp to each automated commit. You may choose to keep this feature as it enhances the clarity of your commit history.

8. **Commit Interval Tracking (Optional)**:
   If you want to prevent overcommitting, you can implement a mechanism that tracks the last commit time and enforces a commit limit interval.

9. **Contributing (Optional)**:
   If you have ideas to improve the Auto-Committer workflow or enhance the experience, you can contribute to the project. You can open an issue to discuss your ideas or directly submit a pull request with your improvements.

10. **License**:
   The "Auto-Committer" project is licensed under the MIT License, which allows you to use and modify the code freely. Ensure you comply with the license terms.

11. **Give it a Star**:
    If you find the "Auto-Committer" project helpful, consider giving it a ⭐️ on GitHub.


## Improvement Ideas

To enhance the Auto-Committer workflow, we made several improvements:

- **Use GitHub Secrets**: Git credentials (username and email) and the Personal Access Token (PAT) are securely stored as GitHub Secrets for a safer workflow.

- **Limit Commits**: Automated commits are now limited to specific intervals (06:00 AM - 06:00 PM UTC) to avoid excessive commits.

- **Commit Timestamp**: Each automated commit includes the timestamp of when it was made, making it easier to track commit times.

- **Commit Interval Tracking**: The workflow now tracks the last commit time and enforces a commit limit interval to prevent overcommitting.

## Contributing

Contributions to this project are welcome! If you have ideas to improve the automation or enhance the experience, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE), allowing you to use and modify the code freely.

---

<div align="center">
  <p>If you find this project helpful, please consider giving it a ⭐️</p>
  <p>Follow me on GitHub <a href="https://github.com/themuuln">here</a></p>
</div>
Sat May 18 05:55:19 UTC 2024
Sat May 18 06:09:13 UTC 2024
Sat May 18 06:26:44 UTC 2024
Sat May 18 06:34:22 UTC 2024
Sat May 18 06:40:41 UTC 2024
Sat May 18 08:20:22 UTC 2024
Sat May 18 08:30:58 UTC 2024
Sat May 18 08:38:38 UTC 2024
Sat May 18 08:45:25 UTC 2024
Sat May 18 08:52:57 UTC 2024
Sat May 18 09:00:23 UTC 2024
Sat May 18 09:18:40 UTC 2024
Sat May 18 09:26:08 UTC 2024
Sat May 18 09:33:40 UTC 2024
Sat May 18 09:41:01 UTC 2024
Sat May 18 09:48:16 UTC 2024
Sat May 18 09:55:41 UTC 2024
Sat May 18 10:09:12 UTC 2024
Sat May 18 10:25:16 UTC 2024
Sat May 18 10:32:32 UTC 2024
Sat May 18 10:39:30 UTC 2024
Sat May 18 10:47:07 UTC 2024
Sat May 18 10:54:18 UTC 2024
Sat May 18 11:04:41 UTC 2024
Sat May 18 11:15:58 UTC 2024
Sat May 18 11:22:57 UTC 2024
Sat May 18 11:29:59 UTC 2024
Sat May 18 11:37:10 UTC 2024
Sat May 18 11:44:25 UTC 2024
Sat May 18 11:51:36 UTC 2024
Sat May 18 11:58:58 UTC 2024
Sat May 18 12:27:06 UTC 2024
Sat May 18 12:47:31 UTC 2024
Sat May 18 12:58:45 UTC 2024
Sat May 18 13:15:34 UTC 2024
Sat May 18 13:24:30 UTC 2024
Sat May 18 13:32:17 UTC 2024
Sat May 18 13:39:22 UTC 2024
Sat May 18 13:46:45 UTC 2024
Sat May 18 13:53:57 UTC 2024
Sat May 18 14:06:24 UTC 2024
Sat May 18 14:21:51 UTC 2024
Sat May 18 14:29:02 UTC 2024
Sat May 18 14:36:04 UTC 2024
Sat May 18 14:43:05 UTC 2024
Sat May 18 14:50:07 UTC 2024
Sat May 18 14:57:05 UTC 2024
Sat May 18 15:13:05 UTC 2024
Sat May 18 15:25:30 UTC 2024
Sat May 18 15:32:54 UTC 2024
Sat May 18 15:40:15 UTC 2024
Sat May 18 15:47:21 UTC 2024
Sat May 18 15:54:33 UTC 2024
Sat May 18 16:08:26 UTC 2024
Sat May 18 16:26:12 UTC 2024
Sat May 18 16:34:54 UTC 2024
Sat May 18 16:41:53 UTC 2024
Sat May 18 16:49:02 UTC 2024
Sat May 18 16:56:03 UTC 2024
Sat May 18 17:08:22 UTC 2024
Sat May 18 17:22:53 UTC 2024
Sat May 18 17:29:55 UTC 2024
Sat May 18 17:37:18 UTC 2024
Sat May 18 17:44:26 UTC 2024
Sat May 18 17:51:40 UTC 2024
Sat May 18 17:58:55 UTC 2024
Sat May 18 18:19:13 UTC 2024
Sat May 18 18:30:36 UTC 2024
Sat May 18 18:37:56 UTC 2024
Sat May 18 18:44:59 UTC 2024
Sat May 18 18:51:59 UTC 2024
Sat May 18 18:59:18 UTC 2024
Sat May 18 19:11:32 UTC 2024
Sat May 18 19:18:44 UTC 2024
Sat May 18 19:25:47 UTC 2024
Sat May 18 19:33:37 UTC 2024
Sat May 18 19:40:53 UTC 2024
Sat May 18 19:48:03 UTC 2024
Sat May 18 19:55:13 UTC 2024
Sat May 18 20:09:37 UTC 2024
Sat May 18 20:22:21 UTC 2024
Sat May 18 20:29:24 UTC 2024
Sat May 18 20:36:39 UTC 2024
Sat May 18 20:43:48 UTC 2024
Sat May 18 20:50:55 UTC 2024
Sat May 18 20:58:14 UTC 2024
Sat May 18 21:11:41 UTC 2024
Sat May 18 21:20:56 UTC 2024
Sat May 18 21:28:05 UTC 2024
Sat May 18 21:35:36 UTC 2024
Sat May 18 21:42:32 UTC 2024
Sat May 18 21:49:48 UTC 2024
Sat May 18 21:57:17 UTC 2024
Sat May 18 22:10:30 UTC 2024
Sat May 18 22:25:24 UTC 2024
Sat May 18 22:33:12 UTC 2024
Sat May 18 22:40:20 UTC 2024
Sat May 18 22:47:48 UTC 2024
Sat May 18 22:54:53 UTC 2024
Sat May 18 23:07:29 UTC 2024
Sat May 18 23:20:29 UTC 2024
Sat May 18 23:27:38 UTC 2024
Sat May 18 23:37:04 UTC 2024
Sat May 18 23:44:14 UTC 2024
Sat May 18 23:51:34 UTC 2024
Sat May 18 23:58:56 UTC 2024
Sun May 19 01:11:59 UTC 2024
Sun May 19 02:06:45 UTC 2024
Sun May 19 02:34:15 UTC 2024
Sun May 19 02:44:45 UTC 2024
Sun May 19 02:51:55 UTC 2024
Sun May 19 02:59:09 UTC 2024
Sun May 19 03:18:17 UTC 2024
Sun May 19 03:29:19 UTC 2024
Sun May 19 03:36:34 UTC 2024
Sun May 19 03:43:46 UTC 2024
Sun May 19 03:50:48 UTC 2024
Sun May 19 03:57:56 UTC 2024
Sun May 19 04:16:42 UTC 2024
Sun May 19 04:30:16 UTC 2024
Sun May 19 04:38:44 UTC 2024
Sun May 19 04:45:39 UTC 2024
Sun May 19 04:53:05 UTC 2024
Sun May 19 05:00:20 UTC 2024
Sun May 19 05:17:06 UTC 2024
Sun May 19 05:28:37 UTC 2024
Sun May 19 05:36:08 UTC 2024
Sun May 19 05:43:23 UTC 2024
Sun May 19 05:50:28 UTC 2024
Sun May 19 05:57:53 UTC 2024
Sun May 19 06:16:55 UTC 2024
Sun May 19 06:30:41 UTC 2024
Sun May 19 06:38:43 UTC 2024
Sun May 19 06:46:07 UTC 2024
Sun May 19 06:53:26 UTC 2024
Sun May 19 07:01:31 UTC 2024
Sun May 19 07:16:41 UTC 2024
Sun May 19 07:23:55 UTC 2024
Sun May 19 07:31:16 UTC 2024
Sun May 19 07:38:33 UTC 2024
Sun May 19 07:45:55 UTC 2024
Sun May 19 07:53:07 UTC 2024
Sun May 19 08:00:12 UTC 2024
Sun May 19 08:20:07 UTC 2024
Sun May 19 08:29:09 UTC 2024
Sun May 19 08:37:12 UTC 2024
Sun May 19 08:44:40 UTC 2024
Sun May 19 08:51:53 UTC 2024
Sun May 19 08:59:07 UTC 2024
Sun May 19 09:16:44 UTC 2024
Sun May 19 09:26:14 UTC 2024
Sun May 19 09:35:19 UTC 2024
Sun May 19 09:42:26 UTC 2024
Sun May 19 09:49:25 UTC 2024
Sun May 19 09:56:38 UTC 2024
Sun May 19 10:10:56 UTC 2024
Sun May 19 10:26:15 UTC 2024
Sun May 19 10:33:29 UTC 2024
Sun May 19 10:40:46 UTC 2024
Sun May 19 10:47:44 UTC 2024
Sun May 19 10:54:56 UTC 2024
Sun May 19 11:07:32 UTC 2024
Sun May 19 11:18:52 UTC 2024
Sun May 19 11:26:00 UTC 2024
Sun May 19 11:33:49 UTC 2024
Sun May 19 11:41:11 UTC 2024
Sun May 19 11:48:27 UTC 2024
Sun May 19 11:55:31 UTC 2024
Sun May 19 12:15:45 UTC 2024
Sun May 19 12:41:54 UTC 2024
Sun May 19 12:54:55 UTC 2024
Sun May 19 13:07:41 UTC 2024
Sun May 19 13:21:07 UTC 2024
Sun May 19 13:28:09 UTC 2024
Sun May 19 13:36:06 UTC 2024
Sun May 19 13:43:02 UTC 2024
Sun May 19 13:50:12 UTC 2024
Sun May 19 13:57:36 UTC 2024
Sun May 19 14:11:48 UTC 2024
Sun May 19 14:25:13 UTC 2024
Sun May 19 14:32:39 UTC 2024
Sun May 19 14:39:49 UTC 2024
Sun May 19 14:47:19 UTC 2024
Sun May 19 14:54:31 UTC 2024
Sun May 19 15:07:14 UTC 2024
Sun May 19 15:21:00 UTC 2024
Sun May 19 15:28:07 UTC 2024
Sun May 19 15:36:46 UTC 2024
Sun May 19 15:43:52 UTC 2024
Sun May 19 15:50:53 UTC 2024
Sun May 19 15:57:54 UTC 2024
Sun May 19 16:16:22 UTC 2024
Sun May 19 16:30:53 UTC 2024
Sun May 19 16:39:56 UTC 2024
Sun May 19 16:47:04 UTC 2024
Sun May 19 16:54:17 UTC 2024
Sun May 19 17:06:32 UTC 2024
Sun May 19 17:20:55 UTC 2024
Sun May 19 17:28:56 UTC 2024
Sun May 19 17:36:05 UTC 2024
Sun May 19 17:43:02 UTC 2024
Sun May 19 17:50:17 UTC 2024
Sun May 19 17:57:28 UTC 2024
Sun May 19 18:15:53 UTC 2024
Sun May 19 18:29:15 UTC 2024
Sun May 19 18:36:43 UTC 2024
Sun May 19 18:43:56 UTC 2024
Sun May 19 18:51:08 UTC 2024
Sun May 19 18:58:11 UTC 2024
Sun May 19 19:10:21 UTC 2024
Sun May 19 19:17:33 UTC 2024
Sun May 19 19:24:48 UTC 2024
Sun May 19 19:32:07 UTC 2024
Sun May 19 19:39:21 UTC 2024
Sun May 19 19:46:53 UTC 2024
Sun May 19 19:53:55 UTC 2024
Sun May 19 20:07:39 UTC 2024
Sun May 19 20:22:09 UTC 2024
Sun May 19 20:29:09 UTC 2024
Sun May 19 20:37:21 UTC 2024
Sun May 19 20:44:33 UTC 2024
Sun May 19 20:51:53 UTC 2024
Sun May 19 20:59:11 UTC 2024
Sun May 19 21:14:33 UTC 2024
Sun May 19 21:23:33 UTC 2024
Sun May 19 21:30:48 UTC 2024
Sun May 19 21:38:00 UTC 2024
Sun May 19 21:45:15 UTC 2024
Sun May 19 21:52:17 UTC 2024
Sun May 19 21:59:37 UTC 2024
Sun May 19 22:17:25 UTC 2024
Sun May 19 22:30:16 UTC 2024
Sun May 19 22:37:29 UTC 2024
Sun May 19 22:44:43 UTC 2024
Sun May 19 22:51:53 UTC 2024
Sun May 19 22:59:10 UTC 2024
Sun May 19 23:16:34 UTC 2024
Sun May 19 23:28:17 UTC 2024
Sun May 19 23:35:58 UTC 2024
Sun May 19 23:42:57 UTC 2024
Sun May 19 23:50:00 UTC 2024
Sun May 19 23:56:58 UTC 2024
Mon May 20 00:55:08 UTC 2024
Mon May 20 01:51:53 UTC 2024
Mon May 20 02:22:35 UTC 2024
Mon May 20 02:41:16 UTC 2024
Mon May 20 02:48:29 UTC 2024
Mon May 20 02:55:51 UTC 2024
Mon May 20 03:11:54 UTC 2024
Mon May 20 03:26:30 UTC 2024
Mon May 20 03:34:06 UTC 2024
Mon May 20 03:41:12 UTC 2024
Mon May 20 03:48:16 UTC 2024
Mon May 20 03:55:17 UTC 2024
Mon May 20 04:12:08 UTC 2024
Mon May 20 04:28:28 UTC 2024
Mon May 20 04:39:04 UTC 2024
Mon May 20 04:46:05 UTC 2024
Mon May 20 04:53:17 UTC 2024
Mon May 20 05:01:36 UTC 2024
Mon May 20 05:20:59 UTC 2024
Mon May 20 05:31:17 UTC 2024
Mon May 20 05:38:30 UTC 2024
Mon May 20 05:45:49 UTC 2024
Mon May 20 05:53:05 UTC 2024
Mon May 20 06:00:12 UTC 2024
Mon May 20 06:24:28 UTC 2024
Mon May 20 06:36:28 UTC 2024
Mon May 20 06:43:40 UTC 2024
Mon May 20 06:50:51 UTC 2024
Mon May 20 06:57:57 UTC 2024
Mon May 20 07:14:07 UTC 2024
Mon May 20 07:24:04 UTC 2024
Mon May 20 07:31:38 UTC 2024
Mon May 20 07:38:38 UTC 2024
Mon May 20 07:45:47 UTC 2024
Mon May 20 07:52:52 UTC 2024
Mon May 20 08:00:05 UTC 2024
