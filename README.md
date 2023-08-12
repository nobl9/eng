# ENG (Essential Network Gauges)

Gain a better understanding of your network and HTTP endpoints with service level objectives (SLOs) backed by ThousandEyes and Nobl9.

## Prerequisites

The Essential Network Gauges is a work-in-progress to provide the quickest and easiest way for users to get started with their networking SLOs. General requirements include both ThousandEyes and Nobl9 accounts.

If you do not have a ThousandEyes account, you can sign up for a free tier trial [here.](https://www.thousandeyes.com/signup/)

If you do not have a Nobl9 account, you can sign up for a permanent free tier [here.](https://app.nobl9.com/signup/)

## Setting up ThousandEyes

Instructions to come.

## Setting up Nobl9

### sloctl

In order to get the most benefit out of the preconfigured templates and example SLO definitions that ENG provides, you should install the `sloctl` command line tool. With `sloctl` you can interact with the Nobl9 API directly to push the suggested example SLO configuration provided.

You can find full instructions for installing `sloctl` [here.](https://docs.nobl9.com/sloctl-user-guide)

### Example Configurations

Within the [`eng/n9`](https://github.com/nobl9/eng/tree/main/n9) folder you will find two subdirectories: [`examples`](https://github.com/nobl9/eng/tree/main/n9/examples) and [`templates`](https://github.com/nobl9/eng/tree/main/n9/templates).

The `examples` directory contains preconfigured example SLOs that can be directly applied to get you started. Please see the [`examples documentation`](https://github.com/nobl9/eng/tree/main/n9/examples) for more information.

The `templates` directory contains YAML files you can use to more easily get started while specifying your own names, thresholds, values, and time windows. Please see the [`templates documentation`](https://github.com/nobl9/eng/tree/main/n9/templates) for more details.
