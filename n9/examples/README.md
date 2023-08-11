# Examples

These files contain Nobl9 YAML configurations for some basic SLOs sourced from ThousandEyes data. You will have to insert two values:
- In `directs.yaml` you will have to insert your ThousandEyes OAuth Bearer Token
- In `slos.yaml` you will have to insert your test ID numbers for the relevant tests that relate to each SLO.


Once these have been configured (and you have everything configured as per the [initial instructions](https://github.com/nobl9/eng/tree/main#readme)) you can use the following `sloctl` commands:

1. First, you will create a new project named `thousand-eyes` via: `sloctl apply -f project.yaml`
2. Next, you will create a service within the `thousand-eyes` project also named `thousand-eyes` via `sloctl apply -f service.yaml -p thousand-eyes`
3. To add your data source, run `sloctl apply -f direct.yaml`
4. And, finally, create your example SLOs by running `sloctl apply -f slos.yaml`

You may rename any of these objects, in which case you will have to ensure that their references are also updates. For example, if you want a different `project` name, you will need to make sure that your `service`, `direct`, and `slo` objects all reference that different `project` name. If you change the `service` name you will need to ensure all `slo` objects reference that changed `service` name.

### ThousandEyes Tests
To learn more about which ThousandEyes tests Nobl9 supports, please see the documentation [here.](https://docs.nobl9.com/Sources/thousandeyes)
