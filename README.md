# aero

`aero` provides instance metadata in a cloud-agnostic manner.

## Usage

```
$ aero list
address-private
address-public
instance
provider
region
zone

$ aero read provider
amazon

$ aero read address-private
10.0.0.12

$ aero read zone
us-east-1a
```

## FAQ

### What providers are supported?

```
amazon
google
```

### What's with the name?

> Aeromancy is divination conducted by interpreting atmospheric conditions.

— _https://en.wikipedia.org/wiki/Aeromancy_
