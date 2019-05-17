Does not deviate from AzureAD/passport-azure-ad

We have this here to be able to bring in node modules for both the release2x branch at the same time as the up to date (currently 4.0.0) branch.  We still have clients on the WS-Federated model which is obsolete.

package.json: {
    "legacy-passport-azure-ad": "git+ssh://git@github.com/spanops/legacy-passport-azure-ad.git#release2x",
    "passport-azure-ad": "^4.0.0",
}
