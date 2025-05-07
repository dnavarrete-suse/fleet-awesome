### Content Review:

- Readme accuracy
- Content accuracy
- Link validity of repositories
- Validity of examples
- Formatting consistency
- Categorization
- Completeness and suggestions

### Testing

- Environment:
	- Clusters on RKE2, RKE1 will be EOL soon.
	- Two different environments for testing each example:
		- Rancher Prime's latest stable version. Two downstream clusters on Kubernetes's latest minor version available and second latest minor (n, n -1) for it according to the Support Matrix -> Deploy in both Downstream clusters (fleet-default)
		- Rancher Prime's second latest stable minor version ( n -1) on Kubernete's second latest minor version available ( n-1) for it according to the Support Matrix -> Deploy in local cluster (fleet-local)
		 
- Suite (for each example):
	- Content:
		- Description
		- Requirements
	- Deployment -> Is the deployment successful? (OK/KO)
	- Readiness -> Is the recipe functional out of the box? (OK/KO)
	- Flexibility -> Is it possible to do basic changes? (OK/KO) 
	- Errors -> Are there any errors present on the involved components? (OK/KO)
