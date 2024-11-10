## Quickstart

```
git clone https://github.com/Maa-ly/PasswordStore
cd PasswordStore
forge build
```

# Usage

## Deploy (local)

1. Start a local node

```
make anvil
```

2. Deploy

This will default to your local node. You need to have it running in another terminal in order for it to deploy.

```
make deploy
```

## Testing

```
forge test
```

### Test Coverage

```
forge coverage
```

and for coverage based testing: 

```
forge coverage --report debug
```
