# Circuitry

Create living, beautiful documentation for data flows across integrated systems
in a complex enterprise landscape

## Dev, Build and Test

Clone this repo, authorize your Dev Hub, then run the commands below
to spin up a scratch org and start building!

```sh
sfdx force:org:create -f config/project-scratch-def.json -a circ -v mydevhub
sfdx force:source:push -u circ
sfdx force:org:open -u circ
```

## Resources

* [Universal Process Notation (UPN)][3]
* [Scratch Org Definition Configuration Values][2]

[2]: https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_scratch_orgs_def_file_config_values.htm
[3]: https://elements.cloud/2016/06/01/upn/

## Description of Files and Directories

Directory | Description
----- | -----
config | Scratch org definition files
force-app | Meaty metadata (yum!)

## Issues

Take a look at the [Issues] tab on GitHub

[1]: https://github.com/justicenation/sfdx-circuitry/issues
