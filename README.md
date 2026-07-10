# Team Compass for the Jupyter AI project


## How to:

### Initialize HackMD meeting notes

Initialize meeting notes on HackMD by navigating to the "Actions" tab of this repo.
Then select "Setup / sync meeting notes" on the left panel.
Now click "Run workflow" in the main workflow listing panel.
Finally, fill in the kind of meeting you're initializing and the date, and click "Run workflow".

<details>
  <summary>Screenshot</summary>
  <img src="https://github.com/user-attachments/assets/db567500-48ee-4e32-8cf3-5eab01cce96c">
</details>

A Pull Request and HackMD document will be created.
Visit the PR to find the HackMD link.

### Sync meeting notes from HackMD to GitHub

When you're ready to sync data from HackMD back to GitHub, comment in the PR with `/bot please sync notes`.
See [this PR](https://github.com/geojupyter/geojupyter.org/pull/32) for an example.

> [!NOTE]
> This job may rarely fail with e.g. 403 response from HackMD.
> In the past, re-running the job has worked.

Review the PR, ensure it passes checks, and merge to update the website.
