CF Buildpack mule
=================

Deploy mule apps to Cloud Foundry

```
git clone https://github.com/srinivasahelwar/mulesoft-buildpack
cd mulesoft-buildpack
cf push bookstore -i 1 -m 512M -b https://github.com/srinivasahelwar/mulesoft-buildpack -p examples/bookstore/bookstore.zip  -n bookstore-srini
```
