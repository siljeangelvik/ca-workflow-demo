### Goal

To improve the quality of an existing `environment` by establishing useful `workflows` that make the development process
more efficient.

### Brief

In order to complete this task, you will need to select an existing `JavaScript` project that has:

1. API calls to `CRUD` an item
2. API call to `authenticate` a user
3. Does not belong to you

~~You may use another student’s project or a project provided by your teacher.~~  
Fork project from [NoroffFEU/social-media-client](https://github.com/NoroffFEU/social-media-client)

**The following workflows/hooks are required:**

1. Project is configured to run Prettier on commit
2. Project is configured to run ESLint on commit
3. Project is configured to run Jest on commit
4. Project is configured to deploy to pages on merge to default

**The following file changes are required:**

1. Project readme file is updated to include new configuration information and status badges
2. Project is configured for hosting (e.g. CDN links or a Bundler)

**The following features must be automatically tested with unit tests:**

1. The login function returns a valid token when provided with valid credentials
2. The logout function clears the token from browser storage
3. The create item function creates a new item on the API

The following features must be automatically tested with end-to-end tests:

1. The login form validates user inputs correctly based on API restrictions
2. The create item form validates user inputs correctly based on API restrictions
3. The logout button logs the user out when clicked

If there are bugs, concerns or problems with the repository you are working on, make sure to list these as `issues`
using
the Issues tab in the repository. It is not your responsibility to resolve these issues but they must be logged if
discovered.

### Delivery

* Please deliver an open Pull Request from branch `workflow` into the target project’s default branch.
* Please post your PR to the peer review forum and review 2 other submissions.
* If you would like a teacher review please request this at least 5 days before the deadline.
* You must complete the course evaluation to unlock delivery.