# Accelerator Log

## Options
```json
{
  "bsGitBranch" : "main",
  "projectName" : "react-frontend",
  "artifactId" : "react-frontend",
  "backendService" : "java-rest-service-azure.mae",
  "bsGitRepository" : "github.com?owner=Mpluya&repo=react-frontend"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(GeneratorValidationTransform, UniquePath)
┃ ┏ ┏ engine.transformations[0].validated (Combo)
┃ ┃ ┃  Info Combo running as Let
┃ ┃ ┃ engine.transformations[0].validated.delegate (Let)
┃ ┃ ┃ Debug Adding symbol backendServiceResourceName with value 'java-rest-service-azure.mae'
┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in (Chain)
┃ ┃ ┃ ┃  Info Running Chain(Combo, Combo, Combo, Combo, Provenance)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[0].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[0].delegate.transformations[0] (ReplaceText)
┃ ┃ ┃ ┃ ┗ ┗  Info Will replace [http://backend->http://java-rest-ser...(truncated)]
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[1] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[1].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[1].delegate.transformations[0] (ReplaceText)
┃ ┃ ┃ ┃ ┗ ┗  Info Will replace [react-frontend->react-frontend]
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[2] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[2].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[2].delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(InvokeFragment, Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[2].delegate.transformations[0].sources[0] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[2].delegate.transformations[0].sources[0].validated (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#bsGitRepository != null) evaluated to true
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Let
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[2].delegate.transformations[0].sources[0].validated.delegate (Let)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Adding symbol repoUrl with value 'https://github.com?owner=Mpluya&repo=react-frontend'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[2].delegate.transformations[0].sources[0].validated.delegate.in (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(OpenRewriteRecipe, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ╺ engine.transformations[0].validated.delegate.in.transformations[2].delegate.transformations[0].sources[0].validated.delegate.in.transformations[0] (OpenRewriteRecipe)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[2].delegate.transformations[0].sources[0].validated.delegate.in.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗ ┗  Info Will replace regex '(?<beforeBranch>[\s\S]+)(?<branch>branch: [\S]+)(?<rest>[\S\s]*)' with '${beforeBranch}branc...(truncated)'
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[2].delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[2].delegate.transformations[0].sources[1].delegate (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug DeploymentTopology.png matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug package-lock.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug tsconfig.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug public/favicon.ico matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug public/logo192.png matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug public/logo512.png matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug public/robots.txt matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/App.test.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/App.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/Layout.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/index.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/index.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/react-app-env.d.ts matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/reportWebVitals.ts matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/setupTests.ts matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug tekton/Dockerfile matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug tekton/README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug tekton/react-test-pipeline.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/api/CustomerProfileDomain.test.ts matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/api/CustomerProfileDomain.ts matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/api/CustomerProfileService.pact.test.ts matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/api/CustomerProfileService.ts matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/components/ErrorMessage.test.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/components/ErrorMessage.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/components/Navigation.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/components/Navigation.test.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/components/Navigation.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/components/PageHeader.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/components/PageHeader.test.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/components/PageHeader.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/pages/create-customer-profile/CreateCustomerProfileForm.test.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/pages/create-customer-profile/CreateCustomerProfileForm.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/pages/create-customer-profile/CreateCustomerProfilePage.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/pages/create-customer-profile/CreateCustomerProfilePage.test.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/pages/create-customer-profile/CreateCustomerProfilePage.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/pages/list-customer-profile/CustomerProfiles.test.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/pages/list-customer-profile/CustomerProfiles.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/pages/list-customer-profile/CustomerProfilesTable.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/pages/list-customer-profile/CustomerProfilesTable.test.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/pages/list-customer-profile/CustomerProfilesTable.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/pages/list-customer-profile/fetchCustomerProfiles.ts matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug nginx.conf matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug package.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug public/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug public/manifest.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[2].delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/pages/list-customer-profile/fetchCustomerProfiles.ts', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/pages/list-customer-profile/CustomerProfiles.test.tsx', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/pages/create-customer-profile/CreateCustomerProfileForm.test.tsx', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/Layout.tsx', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/pages/list-customer-profile/CustomerProfilesTable.tsx', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/components/Navigation.test.tsx', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'public/robots.txt', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/pages/create-customer-profile/CreateCustomerProfilePage.tsx', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/components/ErrorMessage.test.tsx', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/api/CustomerProfileDomain.test.ts', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'public/logo512.png', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'public/favicon.ico', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'LICENSE', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/pages/list-customer-profile/CustomerProfilesTable.css', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'nginx.conf', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/components/PageHeader.test.tsx', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'DeploymentTopology.png', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/api/CustomerProfileService.pact.test.ts', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'README.md', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/App.test.tsx', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/components/PageHeader.tsx', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'tsconfig.json', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'tekton/README.md', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'tekton/Dockerfile', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/components/ErrorMessage.tsx', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gitignore', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'package-lock.json', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/pages/list-customer-profile/CustomerProfiles.tsx', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/index.css', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/components/Navigation.css', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/App.tsx', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/api/CustomerProfileDomain.ts', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/components/PageHeader.css', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/pages/create-customer-profile/CreateCustomerProfileForm.tsx', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.tanzuignore', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'public/logo192.png', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'tekton/react-test-pipeline.yaml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/react-app-env.d.ts', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/index.tsx', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'public/index.html', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'public/manifest.json', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/pages/create-customer-profile/CreateCustomerProfilePage.css', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/setupTests.ts', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/components/Navigation.tsx', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'catalog/catalog-info.yaml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'config/workload.yaml', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'package.json', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/pages/list-customer-profile/CustomerProfilesTable.test.tsx', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/api/CustomerProfileService.ts', will use the one appearing first 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/pages/create-customer-profile/CreateCustomerProfilePage.test.tsx', will use the one appearing first 
┃ ┃ ┃ ┃ ┗ ┗ Debug Multiple representations for path 'src/reportWebVitals.ts', will use the one appearing first 
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[3] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.delegate.in.transformations[3].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, Exclude)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[3].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ ┃ Debug src/pages/list-customer-profile/fetchCustomerProfiles.ts matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/pages/list-customer-profile/CustomerProfiles.test.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/pages/create-customer-profile/CreateCustomerProfileForm.test.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/Layout.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/pages/list-customer-profile/CustomerProfilesTable.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/components/Navigation.test.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug public/robots.txt matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/pages/create-customer-profile/CreateCustomerProfilePage.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/components/ErrorMessage.test.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/api/CustomerProfileDomain.test.ts matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug public/logo512.png matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug public/favicon.ico matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/pages/list-customer-profile/CustomerProfilesTable.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug nginx.conf matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/components/PageHeader.test.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug DeploymentTopology.png matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/api/CustomerProfileService.pact.test.ts matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/App.test.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/components/PageHeader.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug tsconfig.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug tekton/README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug tekton/Dockerfile matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/components/ErrorMessage.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug package-lock.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/pages/list-customer-profile/CustomerProfiles.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/index.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/components/Navigation.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/App.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/api/CustomerProfileDomain.ts matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/components/PageHeader.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/pages/create-customer-profile/CreateCustomerProfileForm.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug public/logo192.png matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug tekton/react-test-pipeline.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/react-app-env.d.ts matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/index.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug public/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug public/manifest.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/pages/create-customer-profile/CreateCustomerProfilePage.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/setupTests.ts matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/components/Navigation.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug package.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/pages/list-customer-profile/CustomerProfilesTable.test.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/api/CustomerProfileService.ts matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/pages/create-customer-profile/CreateCustomerProfilePage.test.tsx matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┗ Debug src/reportWebVitals.ts matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.delegate.in.transformations[3].delegate.transformations[1] (Exclude)
┃ ┃ ┃ ┃ ┃ ┃  Info Will exclude [tekton/**]
┃ ┃ ┃ ┃ ┃ ┃ Debug src/pages/list-customer-profile/fetchCustomerProfiles.ts didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/pages/list-customer-profile/CustomerProfiles.test.tsx didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/pages/create-customer-profile/CreateCustomerProfileForm.test.tsx didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/Layout.tsx didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/pages/list-customer-profile/CustomerProfilesTable.tsx didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/components/Navigation.test.tsx didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug public/robots.txt didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/pages/create-customer-profile/CreateCustomerProfilePage.tsx didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/components/ErrorMessage.test.tsx didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/api/CustomerProfileDomain.test.ts didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug public/logo512.png didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug public/favicon.ico didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/pages/list-customer-profile/CustomerProfilesTable.css didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug nginx.conf didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/components/PageHeader.test.tsx didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug DeploymentTopology.png didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/api/CustomerProfileService.pact.test.ts didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/App.test.tsx didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/components/PageHeader.tsx didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug tsconfig.json didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug tekton/README.md matched [tekton/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tekton/Dockerfile matched [tekton/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/components/ErrorMessage.tsx didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug package-lock.json didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/pages/list-customer-profile/CustomerProfiles.tsx didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/index.css didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/components/Navigation.css didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/App.tsx didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/api/CustomerProfileDomain.ts didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/components/PageHeader.css didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/pages/create-customer-profile/CreateCustomerProfileForm.tsx didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug public/logo192.png didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug tekton/react-test-pipeline.yaml matched [tekton/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/react-app-env.d.ts didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/index.tsx didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug public/index.html didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug public/manifest.json didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/pages/create-customer-profile/CreateCustomerProfilePage.css didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/setupTests.ts didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/components/Navigation.tsx didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug package.json didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/pages/list-customer-profile/CustomerProfilesTable.test.tsx didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/api/CustomerProfileService.ts didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/pages/create-customer-profile/CreateCustomerProfilePage.test.tsx didn't match [tekton/**] -> included
┃ ┃ ┃ ┃ ┗ ┗ Debug src/reportWebVitals.ts didn't match [tekton/**] -> included
┃ ┗ ┗ ┗ ╺ engine.transformations[0].validated.delegate.in.transformations[4] (Provenance)
┗ ╺ engine.transformations[1] (UniquePath)
```
