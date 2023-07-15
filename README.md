![demo](./demo.gif)

# WP-Sync: WordPress Migration Helper

This script is designed to provide a faster and easier solution for migrating WordPress websites. It facilitates the synchronization of a local WordPress environment to a remote environment. Additionally, the script includes intelligent functionality to detect the presence of Elementor, a popular WordPress page builder, and automatically handles necessary tasks such as replacing URLs and flushing CSS.

## Features

- **Effortless Migration:** With this script, migrating your WordPress website becomes a breeze. Say goodbye to manual labor and tedious steps.
- **Saved answers:** This script store user answers for later use, allowing for a more streamlined migration process in the future.
- **Synchronization and Overwriting:** The script seamlessly synchronizes your local WordPress environment with a remote environment, ensuring that your changes are reflected accurately.
- **Elementor Compatibility:** If Elementor is detected in your WordPress installation, the script goes the extra mile to handle important tasks like replacing URLs and flushing CSS.
- **Time-Saving:** By automating the migration process, this script saves you valuable time that can be better utilized for other important tasks.
- **User-Friendly:** The script is designed with simplicity in mind, making it accessible even for users with limited technical knowledge.
- **Open-Source:** This script is open-source and can be customized according to your specific needs.

## Prerequisites

Before using this script, ensure that you have the following:

- A local WordPress environment set up on your machine.
- A remote WordPress environment where you intend to migrate your website.
- Passwordless access between both environments using RSA keys.
- Basic knowledge of WordPress and website migration concepts.

## Usage

- Clone this repo
- Execute `chmod +x wp-sync` making the script executable
- Execute `bash wp-sync` to run the script
- You can also move this script in your `/usr/local/bin` directory and execute it by typing `wp-sync`.

## Contribute

All suggestions, feedback, or bug reports are welcome. Feel free to submit a PR.

## Disclaimer

Please note that the use of this script is at your own risk. The developers of this script are not liable for any damages or issues that may arise from its use. It is advisable to thoroughly test the script on a non-production environment before applying it to a live website.
