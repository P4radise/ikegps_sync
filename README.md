
Features
- creates new code reviews based for "Ready for Review" issues
- updates issue status when code review is closed
- supports git feature branches (branch tracking reviews are created)
- adds new commits to the reviews in master branch
- adding and removing labels for review:
  + when creating a review depending on the type of code (e.g., when SQL code type, label SQL is added)

  + when the reviewer changes its status to Raised concern (e.g., with the SQL code type and status of Raised concern label SQL is added! and label SQL is deleted)

  + when the issue status changes to in progress, the corresponding label is added
- the appointment of reviewers for review by the type of code that is in review
