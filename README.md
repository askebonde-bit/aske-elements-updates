# Aske Elements update answer

The add-in POSTs to its update service. That service returns this file's contents, unchanged.

- `noupdateavailable` means there is nothing to install.
- An `https` URL that ends in `.pkg` means that package is the update. The add-in downloads it and opens the installer.

Change `response` and the installed copies pick it up. No new add-in build is required.
