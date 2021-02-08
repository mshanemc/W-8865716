# Bug repro

`sfdx force:org:create -d 1 -s -f config/project-scratch-def.json`
`sfdx force:source:deploy -m Group -w 10`

it should only deploy Group, NOT the DataCategoryGroup
