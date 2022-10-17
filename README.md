# insights-client-collection-neofetch

This is a repository demonstrating how to collect data using `insights-client`,
while not relying on the default collection. All specs must be defined and
available in insights-core in order for this manifest to locate them.

## Usage

Run `insights-client --manifest ./manifest.yaml` to run the specs defined in
`manifest.yaml` and upload them. Alternatively, if `insights` is installed,
running `insights collect --manifest ./manifest.yaml` will create a collection,
but not compress it into an archive and upload it.
