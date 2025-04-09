# Program2
The second criteria program

# Branch Structure

This repository uses a hierarchical branching structure to organize content development, starting from the `main` branch as the root. Below is the relationship between the branches:

- **`main`**: The root branch which is unused

  - **`template`**: Branched from `main`, this branch holds the template for documents. Each document is in a different sub-branch to provide granular workflows for each.
  
    - **`UFC`**: Branched from `template`, this branch contains all published versions of `document1`.
    
      - **`review0`**: Branched from a certain version of `document2`for the purpose of developing review comments.
      
      - **`update1`**: Branched from a certain version of `document2`, this branch is a working draft and includes a history of approval actions before publication (merging) to the parent branch.

        - **`update1-review1`**: Branched from a working draft of `document2-update1` for the purpose of developing review comments. Review comments are submitted as pull requests against the parent branch.
       
    - **`UFGS`**: Branched from `template`, this branch contains all published versions of `document2`.
    
      - **`review0`**: Branched from a certain version of `document2`for the purpose of developing review comments.
      
      - **`update1`**: Branched from a certain version of `document2`, this branch is a working draft and includes a history of approval actions before publication (merging) to the parent branch.

        - **`update1-review1`**: Branched from a working draft of `document2-update1` for the purpose of developing review comments. Review comments are submitted as pull requests against the parent branch.
