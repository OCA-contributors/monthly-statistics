OCA Monthly Statistics
======================

This repository will store all the collaborators statistics from OCA that I have been exporting.

If you ask why it is done here...
I made this code some years ago and I proposed it to OCA.
However, due to some struggles on how to handle that, I kept all the code and extraction in my own system.

So now I am sharing it throught this as I am sure that contributors will enjoy.

Glossary
--------

- CPRs: Create Pull Requests
- MPRs: Merged Pull Requests
- Cts: Comments on Pull Requests (Done by the user, received by the organization)
- Reviews: Reviews done on Pull Requests (Done by the user, received by the organization)
- CI: Collaborative Index

Collaborative Index
-------------------
The collaborative index is computed as

$$ \sqrt{CPRs} + MPRs + \sqrt{Cts} + Reviews $$

Organizations
-------------

Organizations are taken from the owner of the branch from the Pull Request.
So, If I create a branch using my own fork, the organization will be my user.
If I use an organization repository, the organization will be my organization.

For the Organization, there relevant values are Merged Pull Requests and Created Pull Requests.
Comments and reviews refer to the number of comments that their PRs have received
