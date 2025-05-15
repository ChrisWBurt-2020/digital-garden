# Digital Garden Starter

A foundational setup for creating your personal digital garden using Obsidian.

This project provides a basic directory structure and initial files to help you get started with organizing your notes, ideas, and knowledge.

## Purpose

A digital garden is a space for learning in public, cultivating notes, and connecting ideas over time. This starter kit aims to bootstrap that process by setting up a structured Obsidian vault and integrating it with GitHub for version control.

## Prerequisites

*   **Obsidian**: You'll need to have Obsidian installed on your computer. You can download it from [obsidian.md](https://obsidian.md/).
*   **Git**: For version control and syncing with GitHub (optional if you only plan to use it locally).

## How to Use This Application (Your Digital Garden)

1.  **Clone the Repository (if you haven't already)**:
    ```bash
    git clone https://github.com/ChrisWBurt-2020/digital-garden.git
    cd digital-garden
    ```

2.  **Open as a Vault in Obsidian**:
    *   Open Obsidian.
    *   Click on "Open another vault".
    *   Select "Open folder as vault".
    *   Navigate to and select the `digital-garden/obsidian-vault` folder from your cloned repository.

3.  **Start Exploring and Adding Notes**:
    *   The `obsidian-vault/index.md` file is your homepage. You can customize it to navigate your garden.
    *   The vault is pre-configured with the following top-level folders:
        *   `00-inbox`: For quick notes and unprocessed thoughts.
        *   `01-articles`: For longer-form articles or essays.
        *   `02-figma-inspo`: For design inspiration, potentially linked to Figma exports.
        *   `03-code-snippets`: For useful pieces of code.
    *   Begin creating new notes, linking them together using `[[wikilinks]]`, and organizing them into these folders or new ones you create.

## User Experience (UX) Expectation

*   **Local-First Knowledge Management**: Your primary interaction will be within the Obsidian application on your local machine. This provides a fast, private, and highly customizable note-taking environment.
*   **Interconnected Thinking**: The core UX revolves around creating and linking notes. Use bi-directional links (`[[Your Note Title]]`) to connect ideas. Explore the Graph View in Obsidian to visualize these connections.
*   **Personalization**: Obsidian is highly extensible with plugins. You are encouraged to explore and install plugins (like Daily Notes, Dataview, etc., as mentioned in the original `instructions.md`) to tailor the experience to your workflow.
*   **Content Creation and Curation**: You will be actively writing, editing, and organizing markdown files. The structure provided is a starting point; feel free to adapt it.
*   **Version Control (Optional but Recommended)**: By committing your changes to Git and pushing to GitHub, you create backups and a history of your garden's growth. This also opens possibilities for collaboration or publishing if desired.

## Further Steps and Advanced Customization

This starter kit lays the groundwork. For more advanced features and to fully realize your digital garden, refer to the `../instructions.md` file (located outside the Obsidian vault, in the root of this repository). It contains a checklist for:

*   Configuring specific Obsidian plugins.
*   Integrating with Figma for design assets.
*   Setting up automated backups.
*   Optionally turning your digital garden into a publicly accessible website using static site generators.

Happy gardening!
