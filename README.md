# presentation-rse-cop-urssi-rse

Slides by @JessMurphy and @sdslack for presentation and discussion with the
CU DBMI RSE-CoP about research software engineering best practices, based on
 the 2026 URSSI summer school:
 https://github.com/si2-urssi/summerschool-June2026.

# Setup

1. Install [Quarto](https://quarto.org/) on your system, if not installed
    already.

2. Git clone this repository:

```bash
git clone git@github.com:sdslack/presentation-rse-cop-urssi-rse.git
cd presentation-rse-cop-urssi-rse

```

3. Run the following command to render the slides:

```bash
quarto render presentation.qmd

```

# Steps

1. Create a branch.

2. Commit changes.

Preview changes during local development by running `quarto preview`. 

3. Push branch to GitHub.

4. Open a pull request, which will trigger GitHub Actions to render the slides.

5. Once happy with the changes, merge the pull request into main. This will
    trigger GitHub Actions to render the slides again and deploy them to GitHub
    Pages.

