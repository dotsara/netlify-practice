# Netlify practice

I've used Netlify before, but only after it was setup. This repo is to practice setting it up in the first place. 

## Changelog

<details>
<summary>Friday, 25 March 2022</summary>

- Created the repo… well, _initialized_ the repo from the command line. (Until I created the repo in the GitHub UI--skipping the optional steps--, I couldn't push the new README, etc. to it.)
- Updated the repo settings (no squashing or rebasing; drop wiki & projects); also updated `.git/config` to use my signing key.
   * 🚫 updating `.git/config` wasn't the forcing-function I thought it would be--I wasn't prompted by Terminal to enter my passphrase on that commit.
   * 🚫 I tried again, this time using `git commit -S -am` but that didn't do it, either. 
   * 🚫 I'm trying one more time, but after having restarted my machine (my GPG credentials expire upon system restart). Fingers crossed.
   * 🚫 Naturally, when I re-read [GitHub's documentation on signing commits](https://docs.github.com/en/authentication/managing-commit-signature-verification/signing-commits), I see the tip about configuring a local repo to sign commits by default. I don't remember doing this for work, but I'll try it, now!
   * 🚫 Trying again, this time after adding a **Branch protection rule** for `main`, requiring signed commits. 
   * 🚫 Continuing to (try to) read closely and [follow directions](https://docs.github.com/en/authentication/managing-commit-signature-verification/telling-git-about-your-signing-key), I've tried the "tell Git which key to use" step with the `git config --local user.signingkey ####` command. (The doc uses `--global` but that's not useful for me here.) 
   * So far nothing's working and I want to get to actually using Netlify, so I'm tabling the issue for now.
</details>
<br>
## Resources

- [Netlify](https://netlify.com): for deployment
- [Bulma](https://bulma.io): frontend framework
