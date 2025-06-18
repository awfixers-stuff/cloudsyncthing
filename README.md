# Rsync-Style Backup Service with GUI and AppIndicator

This project provides a user-friendly, graphical interface for backing up your files and drives to cloud storage. Inspired by the simplicity and power of `rsync`, it allows you to easily synchronize your entire drive, selected drives, or specific folders to a remote S3, Cloudflare R2, or DigitalOcean Spaces bucket.

## Features

- **Rsync-Style Synchronization:** Efficiently sync only changed files, minimizing bandwidth and storage usage.
- **Graphical User Interface:** No need to use the command line—manage your backups with an intuitive GUI.
- **AppIndicator Integration:** Runs in your system tray/task bar for quick access and background operation.
- **Flexible Source Selection:** Choose to back up your whole drive, multiple drives, or just specific folders.
- **Cloud Storage Support:** Seamlessly connect to S3, R2, or Spaces buckets for remote backups.
- **Optional Encryption:** Secure your data with built-in encryption before uploading to the cloud.
- **Automated Scheduling:** Set up regular backup intervals to keep your data safe without manual intervention.

## Getting Started

1. **Install the application** on your system.
2. **Connect your cloud storage** by entering your S3/R2/Spaces credentials.
3. **Select the files, folders, or drives** you want to back up.
4. **Enable encryption** if you want your backups to be protected.
5. **Start the backup** or schedule it to run automatically.

The appindicator in your task bar will show the current backup status and provide quick access to settings and logs.

## Why Use This Service?

- **Easy to Use:** No complex commands—just point, click, and back up.
- **Secure:** Optional encryption ensures your data is safe, even in the cloud.
- **Efficient:** Only changed files are uploaded, saving time and resources.
- **Versatile:** Works with multiple cloud providers and supports various backup strategies.

## License

MIT License

## Contributing

Contributions are welcome! Please open issues or submit pull requests to help improve the project.
