# OCI Helm Charts Mirror

> [!IMPORTANT]
> This is a stop-gap mirror of OCI Helm Charts that can be used until maintainers of upstream charts publish them. See the issue [here](https://github.com/onedr0p/charts-mirror/issues/6) for tracking the progress of upstream support for OCI charts.

## Contributing

1. Verify the chart doesn't already have an official OCI Helm Chart.
2. Create a new directory under `charts/` with the chart name.
3. Add a `metadata.yaml` to that new directory file with the contents:

    ```yaml
    ---
    registry: <registry-url>
    chart: <chart-name>
    version: <chart-version>
    ```

4. Open a PR with the link in the description to the upstream issue tracking OCI Helm Chart support.
