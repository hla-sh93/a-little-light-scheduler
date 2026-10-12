# A Little Light scheduler

This public repository contains only the GitHub Actions schedule for the private **A Little Light** Telegram service. The application, 365-message collection, recipient configuration and provider credentials are not stored here.

The workflow calls the protected production dispatcher at 08:00, 08:20 and 08:40 Baghdad time. The application uses an atomic Neon claim, so only the first valid attempt for a recipient and date can contact Telegram.
