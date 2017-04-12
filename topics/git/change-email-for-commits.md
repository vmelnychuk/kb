git filter-branch -f --env-filter \
"GIT_AUTHOR_NAME='New Author'; GIT_AUTHOR_EMAIL='new_emailk@example.com'; \
GIT_COMMITTER_NAME='Old Commiter'; GIT_COMMITTER_EMAIL='old_email@example.com';" HEAD