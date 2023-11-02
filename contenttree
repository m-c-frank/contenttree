#!/bin/bash

# Check if tree command is available
if ! command -v tree &> /dev/null
then
    echo "tree command could not be found. Please install it."
    exit
fi

# Display tree structure
tree $(git ls-files --others --exclude-standard --cached | tr '\n' ' ')

# Display file names and content
git ls-files --others --exclude-standard --cached | while read file; do 
    echo "\n\n=== $file ===\n"; 
    cat "$file"; 
done
