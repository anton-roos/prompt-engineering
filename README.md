# Introduction to Prompt Engineering

*Learn the basics of crafting effective prompts for AI models like Grok or ChatGPT.*

## Welcome

Prompt engineering is the art of designing inputs (prompts) to get the best outputs from AI models. This course will teach you foundational techniques through hands-on exercises in GitHub.

- **Who is this for**: Beginners interested in AI, developers, writers, or anyone curious about interacting with large language models.
- **What you'll learn**: Key concepts like zero-shot prompting, few-shot prompting, chain-of-thought, and best practices for clear prompts.
- **What you'll build**: A `prompts.md` file documenting various prompt techniques and their results.
- **Prerequisites**: Access to an AI tool (e.g., grok.com, ChatGPT). No prior GitHub experience needed—we'll guide you.
- **How long**: Less than 30 minutes, with 4 steps.

### How to start this course

1. Above this section, locate the menu that begins with **Start course** ... right-click **Start course** and open the link in a new tab.
2. In the new tab, follow the prompts to create a copy of this template in your account. We recommend creating a public repository—private repositories may limit functionality.
3. After your copy is created, wait about 20 seconds, then refresh this page (the one you're reading right now). GitHub Actions will automatically update this section with the next steps. :balloon:

_If after 2 minutes this doesn't happen, please refresh the page and see [troubleshooting](https://docs.github.com/actions/managing-workflow-runs/reviewing-workflow-run-history) below._

> [!NOTE]
> Throughout this course, you'll see a :keyboard: emoji followed by **Activity**. This indicates a task for you to complete. Follow the instructions, and GitHub Actions will detect your progress.

## Step 1: Your First Prompt (Zero-Shot Prompting)

*You've created your repository—great start! Now let's write your first prompt.*

Zero-shot prompting means giving the AI a task without examples—it relies on the model's pre-training.

### :keyboard: Activity: Create and commit a basic prompt

1. Create a new file called `prompts.md`.
2. Add the following content:
```text
# My Prompts

## Zero-Shot Prompt
Prompt: "Explain quantum computing in simple terms."

Expected Output: [Paste the AI's response here after testing]
```
3. Test the prompt in your AI tool (e.g., copy-paste into Grok) and paste the output.
4. Commit the file directly to the `main` branch.

Wait about 20 seconds, then refresh this page. GitHub Actions will update to the next step.

<details>
<summary>Troubleshooting</summary>
If nothing happens, check the [Actions tab](https://github.com/YOUR_USERNAME/introduction-to-prompt-engineering/actions) to see if workflows are running.
</details>

## Step 2: Add Examples (Few-Shot Prompting)

*Nice commit! You've used zero-shot prompting. Now let's improve it with examples.*

Few-shot prompting provides 1-3 examples in the prompt to guide the AI's response style.

### :keyboard: Activity: Edit the file and create a branch

1. Create a new branch named `few-shot`.
2. Edit `prompts.yml` to add a new section:
```yml
## Few-Shot Prompt

Prompt:

Example 1: Explain gravity simply: Gravity is the force that pulls objects toward each other.

Example 2: Explain electricity simply: Electricity is the flow of electric charge.

Explain quantum computing simply:"
Expected Output: [Paste the AI's response here after testing]
```
3. Test the prompt and paste the output.
4. Commit to the `few-shot` branch.

GitHub Actions will detect the branch and update progress. Refresh in 20 seconds.

## Step 3: Chain-of-Thought Prompting

*Branch created successfully! Now let's chain reasoning steps.*

Chain-of-thought (CoT) prompting encourages the AI to think step-by-step for better reasoning.

### :keyboard: Activity: Open a pull request

1. Open a pull request from `few-shot` to `main`.
2. In the PR description, add a CoT prompt example and test it:

    ## Chain-of-Thought Prompt
    Prompt: "Solve this: What is 15% of 200? Think step-by-step."
    
    Expected Output: [Paste the AI's response here]

3. Submit the PR (don't merge yet).

Actions will comment on your PR with feedback. Refresh to see.

## Step 4: Best Practices and Merge

*PR opened—almost done! Apply best practices like clarity and specificity.*

### :keyboard: Activity: Merge and finalize

1. Edit `prompts.md` in the PR to add a best practices section:

    ## Best Practices
    - Be specific and clear.
    - Use role-playing, e.g., "You are a teacher..."
    - Iterate on prompts if needed.

2. Merge the pull request.
3. Test one more prompt using all techniques combined.

Actions will detect the merge and mark the course complete.

## Finish

:sparkles: Congratulations! You've completed the introduction to prompt engineering.

You've learned:
- Zero-shot, few-shot, and chain-of-thought prompting.
- Best practices for effective prompts.

You built `prompts.md`—feel free to expand it!

### Next steps
- Explore advanced techniques in [GitHub Docs on AI](https://docs.github.com/en/get-started) or external resources.
- Try more prompts in real projects.
- Share your repo or give feedback by opening an issue here.

If you had trouble, check [GitHub Status](https://www.githubstatus.com/) or [get help](https://docs.github.com/).

© 2025 Hollard