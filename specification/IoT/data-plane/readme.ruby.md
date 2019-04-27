## Ruby

These settings apply only when `--ruby` is specified on the command line.

```yaml
package-name: azure_mgmt_IoT
package-version: 2019-04-26
azure-arm: true
```

### Tag: package-2019-04-26 and ruby

These settings apply only when `--tag=package-2019-04-26 --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

```yaml $(tag) == 'package-2019-04-26' && $(ruby)
namespace: Microsoft.Devices
output-folder: $(ruby-sdks-folder)/IoT
```
