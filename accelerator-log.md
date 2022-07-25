# Accelerator Log

## Options
```json
{
  "deploymentType" : "workload",
  "projectName" : "javascript-frontend-sample"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(GeneratorValidationTransform, UniquePath)
┃ ┏ ┏ engine.transformations[0].validated (Combo)
┃ ┃ ┃  Info Combo running as Chain(Merge(merge), UniquePath(UseLast))
┃ ┃ ┃ engine.transformations[0].validated.merge (Chain)
┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0] (Merge)
┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo, Combo)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Exclude)
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[0].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, Exclude)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[0].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug httpd.toml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug nginx.toml matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug package-lock.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug package.json matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug public/favicon.ico matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug public/index.html matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug public/robots.txt matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/App.css matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/App.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┗ Debug src/index.js matched [**] -> included
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[0].<combo>.transformations[1] (Exclude)
┃ ┃ ┃ ┃ ┃ ┃  Info Will exclude [config/**, catalog/**, DEPLOYING.md, .github/**]
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [config/**, catalog/**, DEPLOYING.md, .github/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [config/**, catalog/**, DEPLOYING.md, .github/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [config/**, catalog/**, DEPLOYING.md, .github/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [config/**, catalog/**, DEPLOYING.md, .github/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug httpd.toml didn't match [config/**, catalog/**, DEPLOYING.md, .github/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug nginx.toml didn't match [config/**, catalog/**, DEPLOYING.md, .github/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug package-lock.json didn't match [config/**, catalog/**, DEPLOYING.md, .github/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug package.json didn't match [config/**, catalog/**, DEPLOYING.md, .github/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug public/favicon.ico didn't match [config/**, catalog/**, DEPLOYING.md, .github/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug public/index.html didn't match [config/**, catalog/**, DEPLOYING.md, .github/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug public/robots.txt didn't match [config/**, catalog/**, DEPLOYING.md, .github/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/App.css didn't match [config/**, catalog/**, DEPLOYING.md, .github/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug src/App.js didn't match [config/**, catalog/**, DEPLOYING.md, .github/**] -> included
┃ ┃ ┃ ┃ ┗ ┗ Debug src/index.js didn't match [config/**, catalog/**, DEPLOYING.md, .github/**] -> included
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#deploymentType == 'workload') evaluated to true
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[1].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Condition (#deploymentType == 'workload') evaluated to true
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[1].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [config/workload.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [config/workload.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug httpd.toml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug nginx.toml didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug package-lock.json didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug package.json didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug public/favicon.ico didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug public/index.html didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug public/robots.txt didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/App.css didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/App.js didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug src/index.js didn't match [config/workload.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[1].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[1].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┃ ┃ ┗ ┗ ┗  Info Will replace [: javascript-frontend-sample->: javascript-fronten...(truncated)]
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#deploymentType == 'workload') evaluated to true
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Condition (#deploymentType == 'workload') evaluated to true
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [catalog/*.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug httpd.toml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug nginx.toml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug package-lock.json didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug package.json didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug public/favicon.ico didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug public/index.html didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug public/robots.txt didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/App.css didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/App.js didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug src/index.js didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┃ ┃ ┗ ┗ ┗  Info Will replace [javascript-frontend-sample->javascript-frontend-...(truncated)]
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[3] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#deploymentType == 'workload') evaluated to true
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Chain(chain))
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[3].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Condition (#deploymentType == 'workload') evaluated to true
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, Chain)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[3].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [DEPLOYING.md]
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug httpd.toml didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug nginx.toml didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug package-lock.json didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug package.json didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug public/favicon.ico didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug public/index.html didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug public/robots.txt didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/App.css didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug src/App.js didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug src/index.js didn't match [DEPLOYING.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[3].<combo>.transformations[1] (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[3].<combo>.transformations[1].transformations[0] (ReplaceText)
┃ ┃ ┃ ┗ ┗ ┗ ┗  Info Will replace [javascript-frontend-sample->javascript-frontend-...(truncated)]
┃ ┗ ┗ ╺ engine.transformations[0].validated.merge.transformations[1] (UniquePath)
┗ ╺ engine.transformations[1] (UniquePath)
```
