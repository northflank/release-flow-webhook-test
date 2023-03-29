# Northflank Release Flow Github Actions Example

Example repository for automatically building & pushing commits to GitHub Container Registry whenever a pull request is opened or updated, then deploys the image on Northflank as a deployment service.

Takes the secret `NF_WEBHOOK`, which should be the URL of the webhook trigger generated in the release flow settings on Northflank.
