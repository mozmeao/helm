# A Repo to hold onto our helm charts

# Packaging
Using helm, package each repo you've changed:
`helm package bedrock/`
(then mv the tar.gz into docs folder)

# Publish
Then create an index file of the charts:
`helm repo index docs/ --url https://mozmeao.github.io/helm`
Then do the typical git add/git commit/git push pattern

