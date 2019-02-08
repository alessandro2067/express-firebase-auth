Add option to detect ID token revocation

## Description
Detect ID token revocation in the Firebase Admin SDK.
https://firebase.google.com/docs/auth/admin/manage-sessions#detect_id_token_revocation_in_the_sdk

## Related Issue
To open.

## Motivation and Context
Detect ID token revocation in the Firebase Admin SDK.

## How Has This Been Tested?
I modifyied my user password.
With option checkRevoked set to false, the token is still valid.
With option checkRevoked set to true, the token is not valid.

## Screenshots (if appropriate):

## Types of changes
<!--- What types of changes does your code introduce? Put an `x` in all the boxes that apply: -->
- [ ] Bug fix (non-breaking change which fixes an issue)
- [X] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to change)

## Checklist:
<!--- Go over all the following points, and put an `x` in all the boxes that apply. -->
<!--- If you're unsure about any of these, don't hesitate to ask. We're here to help! -->
- [X] My code follows the code style of this project.
- [X] My change requires a change to the documentation.
- [X] I have updated the documentation accordingly.
- [X] I have read the **CONTRIBUTING** document.
