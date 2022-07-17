# fleet
Deploy fleet/gameservers in Agones

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add couchpartygames https://couchpartygames.github.io/fleet

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
<alias>` to see the charts.

To install the fleet chart:

    helm install fleet couchpartygames/fleet

To uninstall the chart:

    helm delete fleet
