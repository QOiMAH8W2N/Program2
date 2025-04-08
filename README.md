# Program2
The second criteria program

# Branch Structure

This repository uses a hierarchical branching structure to organize content development, starting from the `main` branch as the root. Below is the relationship between the branches:

- **`main`**: The root branch which is unused

  - **`template`**: Branched from `main`, this branch holds the template for documents. Each document is in a different sub-branch to provide granular workflows for each.
  
    - **`document1`**: Branched from `template`, this branch contains all published versions of `document1`.
    
      - **`document1-update1`**: Branched from a certain version of `document1`, this branch is a working draft and includes a history of approval actions before publication (merging) to the parent branch.

        - **`document1-update1-review1`**: Branched from a working draft of `document1-update1` for the purpose of developing review comments. Review comments are submitted as pull requests against the parent branch.
       
    - **`document2`**: Branched from `template`, this branch contains all published versions of `document2`.
    
      - **`document2-update1`**: Branched from a certain version of `document2`, this branch is a working draft and includes a history of approval actions before publication (merging) to the parent branch.

        - **`document2-update1-review1`**: Branched from a working draft of `document2-update1` for the purpose of developing review comments. Review comments are submitted as pull requests against the parent branch.
