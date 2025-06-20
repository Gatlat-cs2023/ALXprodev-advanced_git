cat > README.md <<EOF
# ALXprodev Advanced Git Repository

This repository demonstrates GitFlow workflow implementation.

## Repository Structure

- `main` branch - Production-ready code
- `develop` branch - Main development branch

## GitFlow Workflow

This project uses GitFlow branching model with:

- Feature branches (`feature/`)
- Release branches (`release/`)
- Hotfix branches (`hotfix/`)
- Support branches (`support/`)

## Installation

1. Clone the repository:
   \`\`\`bash
   git clone git@github.com:your-username/ALXprodev-advanced_git.git
   \`\`\`

2. Initialize GitFlow:
   \`\`\`bash
   git flow init -d
   \`\`\`

## Usage

Standard GitFlow commands apply:

- Start a new feature:
  \`\`\`bash
  git flow feature start FEATURE_NAME
  \`\`\`

- Finish a feature:
  \`\`\`bash
  git flow feature finish FEATURE_NAME
  \`\`\`
EOF