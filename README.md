# GitHubPulseRadar

Dashboard for viewing GitHub release download statistics across multiple repositories at once.

## Features

- View download statistics for multiple GitHub repositories simultaneously
- Auto-fetch on page load
- Total downloads summary
- Responsive grid layout (2 columns on desktop, 1 on mobile)
- LocalStorage persistence for repositories and GitHub token
- No server required - runs entirely in the browser

## Usage

1. Open the page in your browser
2. Add repositories in `owner/repo` format or paste GitHub URLs
3. Statistics load automatically
4. Optionally add a GitHub token for higher rate limits (60 → 5000 requests/hour)

## GitHub Token

Create a token at https://github.com/settings/tokens (no special permissions needed for public repos).

## License

MIT
