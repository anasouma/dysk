# dysk Verification #

## Configuration ##

Modify ./settings.json file by adding your storage account name and key

## Running the verification ##

```
./verify.sh <VERIFY or PERF>
```

Or on the root of this repo 

```
make verify #verification
make verify-perf #perf test
```


> The verification is long running ~5mins. And does not perform storage account clean up. To clean clean remove "dysk" blob container.
