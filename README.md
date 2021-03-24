# continous-security-for-developers
Information about security related tools for developers

# Software composition analysis tools (SCA)
## [OWASP Dependency check](https://owasp.org/www-project-dependency-check/)
There is an [extension](https://marketplace.visualstudio.com/items?itemName=dependency-check.dependencycheck) available for Azure Devops but you can also add it to your yaml-pipeline yourself.

## [SNYK Open source](https://snyk.io/product/open-source-security-management/)
This [page](https://support.snyk.io/hc/en-us/articles/360004127677-Azure-Pipelines-integration) explains how to add it to Azure Devops.

## [WhiteSource Renovate](https://www.whitesourcesoftware.com/free-developer-tools/renovate/)
There is an [extension](https://marketplace.visualstudio.com/items?itemName=jyc.vsts-extensions-renovate-me) available for Azure Devops.


# Static Application Security Testing (SAST)
## [SNYK Code](https://snyk.io/product/snyk-code/)
Currently it can only be used in the [portal](https://snyk.io/) and Eclipse but it will come as an extension to Visual Studio Code soon.

# Dynamic Application Security Testing (DAST)
## [OWASP ZAP](https://owasp.org/www-project-zap/)
This [page](https://medium.com/@ganeshsirsi/how-to-run-owasp-zap-security-tests-part-of-azure-devops-ci-cd-pipeline-484da8793a12) explains how to add it to Azure Devops. There is an [extension](https://marketplace.visualstudio.com/items?itemName=CSE-DevOps.zap-scanner) available.
