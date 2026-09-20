# GitHub Actions Workflow Analysis

## 1. What triggers the workflow?

The workflow starts when code is pushed to the `main` branch or when a pull request is made.

## 2. What are the four main steps?

1. Checkout code
2. Set up the environment
3. Check the website for errors
4. Deploy the website to GitHub Pages

## 3. What does "Checkout code" do?

Checkout code gets the files from the repository so GitHub Actions can use them.

## 4. What is the purpose of the environment configuration?

It sets up everything GitHub Actions needs to run the workflow.

## 5. Why is automated deployment better than manual deployment?

It makes deployment easier and helps prevent mistakes because GitHub does most of the work automatically.

## 6. What happens if you push to a different branch instead of `main`?

The website will not deploy from that branch. The changes need to be merged into `main` first.
