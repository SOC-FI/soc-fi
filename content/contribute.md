---
title: "Contributions welcome"
layout: "single"
---

## List of SOC providers

1. [Fork the source repo](https://github.com/SOC-FI/soc-fi) and then clone the forked repo.

    ```
    gh repo fork https://github.com/SOC-FI/soc-fi --clone
    ```

2. Create a new branch and set upstream to this repo, example:

    ```
    git checkout -b add_accenture
    git remote add upstream https://github.com/SOC-FI/soc-fi
    ```

3. Add a new SOC provider, example:

    ```
    hugo new --kind provider content/providers/accenture.md
    ```

4. Add the company name and website to the created MD file, example:

    ```
    title: (leave it as it was)
    date: (leave it as it was)
    draft: (leave it as it was)
    company: "Accenture"
    website: "https://accenture.com"
    ```

5. Commit, example:

    ```
    git add content/providers/accenture.md
    git commit -S -m "Added Accenture"
    git push -u origin add_accenture
    ```

6. Create a PR on the GitHub page of [the source repo](https://github.com/SOC-FI/soc-fi) by clicking Compare & pull request.
