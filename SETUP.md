# Publish this GitHub profile for @haelkh

GitHub displays the root README of a **public repository named exactly `haelkh`**, owned by `haelkh`, on https://github.com/haelkh.

## Fast option — with GitHub CLI (Windows PowerShell)

1. Install [Git](https://git-scm.com/) and [GitHub CLI](https://cli.github.com/) if needed.
2. Authenticate **as `haelkh`** using `gh auth login` and confirm the login with `gh api user --jq .login`.
3. Extract this ZIP and open PowerShell in the extracted `haelkh-github-profile` folder.
4. Run `./publish.ps1`. It checks your account, creates the missing public profile repository, and pushes the README and local SVG assets.
5. Open https://github.com/haelkh to see the profile.

The script refuses to publish if your currently authenticated GitHub account isn't `haelkh`, and it refuses to overwrite an existing profile repo.

## GitHub website option

1. Sign in as `haelkh` at github.com.
2. Create a **public** repository named **`haelkh`** with a README. GitHub will show that this is a special profile repository.
3. Replace the initial `README.md` with the provided `README.md`.
4. Upload all seven `.svg` images to the **`assets/`** directory. Use **Add file → Upload files** and preserve the exact folder paths.
5. Commit the changes to the default branch and refresh your profile.

## After publishing

- In the profile **Edit profile** screen, use a keyword-focused bio such as: `AI Engineer | LLM Agents • RAG • Applied ML | Python • LangGraph | Building useful AI systems`.
- Set your website or social link to your LinkedIn profile if desired.
- Pin 4–6 repositories: start with `ethrocore-assessment`, `Pneumonia`, `stockMarketPred`, and `Hirlytics-final`; consider `AspireSoftware`.
- Replace the boilerplate README in `Hirlytics-final` and add a real README to `stockMarketPred`. Include architecture diagrams, environment setup, results only when measured, and a short demo where possible.
- **Important:** review your public repositories for API keys, secrets, private datasets, company IP, and confidential work before emphasizing them in applications.

## Design notes

The header, rotating-focus line, pipeline graphic, and four project thumbnails are **self-contained SVGs with embedded CSS animation**, so they don't depend on a third-party uptime or hidden scripts. Most reduced-motion settings are respected.

The bio and project descriptions were based on currently described public repositories and existing professional context. Verify your current employment and education lines and edit them if they change. No benchmark or revenue claims were fabricated.

## Folder layout

```
README.md
assets/
  hero.svg
  focus.svg
  pipeline.svg
  arabic-tts.svg
  vision.svg
  forecast.svg
  hirlytics.svg
publish.ps1
SETUP.md
```
