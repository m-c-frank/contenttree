# contenttree

`contenttree` is a utility designed to display a tree structure of your repository's files and directories while respecting `.gitignore`. It then prints the filename followed by its content for each file. This tool is especially useful for developers and writers who want a quick overview of their project's structure and content, all in one place.

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

**Note Utilities Ecosystem**: `contenttree` is a part of the growing Note Utilities Ecosystem designed to streamline and enhance your note-taking and information processing workflows. Dive in and explore more tools like [conceptsplitter](https://github.com/m-c-frank/conceptsplitter) and [textdownloader](https://github.com/m-c-frank/textdownloader) that can elevate your productivity!

## Contributing

Contributions to the `contenttree` project or the Note Utilities Ecosystem are welcome. If you have ideas for improvements or new features, please feel free to submit issues, suggestions, or pull requests in this repository or contact me!

## License

The `contenttree` project is open-source and available under the [GOS License](LICENSE.md).

## Credits

The `contenttree` project is developed and maintained by [Martin Christoph Frank](https://github.com/m-c-frank). If you have any questions or need assistance, please contact [martin7.frank7@gmail.com](martin7.frank7@gmail.com).