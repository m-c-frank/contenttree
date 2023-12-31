# contenttree

`contenttree` is a utility designed to display a tree structure of your repository's files and directories while respecting `.gitignore`. It then prints the filename followed by its content for each file. This tool is especially useful for developers and writers who want a quick overview of their project's structure and content, all in one place. And then you can also just paste it in ChatGPT to quickly debug your code.

## Features

- Displays a tree structure of your repository's files and directories.
- Respects `.gitignore` settings.
- Prints each file's name followed by its content.
- Integrates seamlessly with any git repository.

## Directory Structure

```bash
.
├── .gitignore           # Git ignore file
├── README.md            # Documentation for contenttree
└── contenttree.sh       # Main script to display tree structure and file content
```

## Setup

1. Clone the repository:

    ```bash
    git clone [repository_url]
    cd contenttree
    ```

2. Make the script executable:

    ```bash
    chmod +x contenttree.sh
    ```

## Usage

1. Navigate to any git repository.

2. Run the `contenttree` script:

   ```bash
   /path/to/contenttree.sh
   ```

3. View the tree structure followed by file names and content.

## Related Tools

<!--START_TOKEN-->
**Note Utilities Ecosystem**: A suite of tools designed to streamline and enhance your note-taking and information processing workflows.

- **[dirbuilder](https://github.com/m-c-frank/dirbuilder)** - Builds a directory structure from `tree`
- **[workflowlibrary](https://github.com/m-c-frank/workflowlibrary)** - Centralizes and synchronizes the "Related Tools" section across the ecosystem.
- **[noteutilsyncer](https://github.com/m-c-frank/noteutilsyncer)** - A centralized tool that automates the synchronization of the "Related Tools" section across READMEs in the noteutils ecosystem.
- **[conceptsplitter](https://github.com/m-c-frank/conceptsplitter)** - Extract atomic concepts from a given text using the OpenAI API.
- **[textdownloader](https://github.com/m-c-frank/textdownloader)** - A browser extension to automatically generate text dumps for processing.
- **[contenttree](https://github.com/m-c-frank/contenttree)** - A utility to print a repository's tree structure and file content
<!--END_TOKEN-->

## Contributing

Contributions to the `contenttree` project or the Note Utilities Ecosystem are welcome. If you have ideas for improvements or new features, please feel free to submit issues, suggestions, or pull requests in this repository or contact me!

## License

The textdownloader browser extension is open-source and licensed under the [GOS License](https://github.com/m-c-frank/textdownloader/blob/main/LICENCE.md).

## Credits

The `contenttree` project is developed and maintained by [Martin Christoph Frank](https://github.com/m-c-frank). If you have any questions or need assistance, please contact [martin7.frank7@gmail.com](martin7.frank7@gmail.com).
