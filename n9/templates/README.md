### Templates

These files contain formatted YAML for the bare minimum configuration required to start measuring an SLO with ThousandEyes data:
- A `project`, which is a logical container for `services`;
- A `service`, which is a logical container for `SLOs`;
- An `SLO`, which contains your actual measurement, threshold, and time window configurations; and,
- A `direct`, which is a direct data integration configuration that allows for Nobl9 to talk to your ThousandEyes account.

By configuring these four objects you can get started with ThousandEyes and Nobl9 today.

For more details about the Nobl9 YAML configuration format, as well as how to configure additional items such as alerts or alert policies, please see the [Nobl9 YAML Guide](https://docs.nobl9.com/yaml-guide).
